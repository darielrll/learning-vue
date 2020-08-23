<template>
    <div class="card col-md-4">
        <div class="card-body">
            <h5 class="card-title">
                {{texto}}
            </h5>
            <p class="card-text">
                "At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium."
            </p>

            <button class="btn btn-primary" v-on:click="letraElegida('A')">Boton A</button> <br/><br/>
            <button class="btn btn-primary" v-on:click="letraElegida('B')">Boton B</button>
        </div>
    </div>
</template>

<script>
export default {
    name: "Opcion1",
    data() {
        return {
            opcion: "xxx",
            texto: "Titular"
        }
    },
    methods: {
        sumar: function() {
            this.opcion = Math.floor(Math.random() * 1000)
        },
        letraElegida: function (letra) {
            this.texto = "Seleccionaste el boton " + letra
        }
    }
}
</script>

<style scoped>

</style>

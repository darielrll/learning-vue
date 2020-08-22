<template>
    <div class="card col-md-4">
        <div class="card-body">
            <h5 class="card-title">
                Opcion 1 {{opcion}}
            </h5>
            <p class="card-text">
                "At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium."
            </p>

            <button class="btn btn-primary" v-on:click="sumar">Opcion 1</button>
        </div>
    </div>
</template>

<script>
export default {
    name: "Opcion1",
    data() {
        return {
            opcion: "xxx"
        }
    },
    methods: {
        sumar: function() {
            this.opcion = Math.floor(Math.random() * 1000)
        }
    }
}
</script>

<style scoped>

</style>

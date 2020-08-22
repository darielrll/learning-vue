<template>
    <div class="card col-md-4">
        <div class="card-body">
            <h5 class="card-title">
                Opcion 2 - {{entradaDeTexto}}
            </h5>
            <form>
                <p class="card-text">
                    "At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium."
                </p>
                <div class="row">
                    <input v-bind:value="entradaDeTexto"/>
                </div>
                <div class="row">
                    <button class="btn btn-primary" v-on:click="entradaDeTexto = 'Nuevo texto'">Opcion 2</button>
                </div>
            </form>
        </div>
    </div>
</template>

<script>
export default {
    name: "Opcion2",
    data() {
        return {
            entradaDeTexto: "*** texto ***"
        }
    }
}
</script>

<style scoped>

</style>

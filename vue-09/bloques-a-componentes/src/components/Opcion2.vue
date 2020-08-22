<template>
    <div class="card col-md-4">
        <div class="card-body">
            <h5 class="card-title">
                Opcion 2
            </h5>
            <form>
                <p class="card-text">
                    "At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium."
                </p>
                <div class="row">
                    <input v-bind:value="entradaDeTexto"/>
                </div>
                <div class="row">
                    <a href="#" class="btn btn-secondary">Opcion 2</a>
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

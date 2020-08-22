<template>
    <div class="card col-md-4">
        <div class="card-body">
            <h5 class="card-title">
                Opcion 3 {{estado}}
            </h5>
            <p class="card-text">
                "At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium."
            </p>
            <input @keypress="estado = 'teclado'" @keypress.enter="estado = 'enter'">
            <a v-on:click="estado = 'click'" v-on:mouseover="estado = 'mouse over'"  class="btn btn-success">Opcion 3</a>
        </div>
    </div>
</template>

<script>
export default {
    name: "Opcion3",
    data() {
        return {
           estado: ""
        }
    }
}
</script>

<style scoped>

</style>

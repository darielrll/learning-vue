<template>
    <div class="card col-md-4">
        <div class="card-body">
            <h5 class="card-title">
                Opcion 1 {{opcion}}
            </h5>
            <p class="card-text">
                "At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident."
            </p>

            <button class="btn btn-primary" v-on:click="opcion='--- CLICK ---'">Opcion 1</button>
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
    }
}
</script>

<style scoped>

</style>

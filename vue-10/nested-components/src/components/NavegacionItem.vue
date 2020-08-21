<template>
    
    <li class="nav-item" v-bind:style="{backgroundColor: colorRandom, border: 'solid 3px yellow'}">
        <a class="nav-link" href="#">{{titulo}}</a>
    </li>
    
</template>

<script>
export default {
    name: "NavegacionItem",
    data() {
        return {
            mostrarActivo: true,
            colorRandom: "#" + Math.floor(Math.random() * 6777215).toString(16)
        }
    },
    props: {
        titulo: String
    }
}
</script>

<style lang="">
    
</style>
<template>
    <ul class="nav">
        <li class="nav-item">
            <a class="nav-link" v-bind:class="{ active : mostrarActivo }" href="#">Active</a>
        </li>
        <li class="nav-item" v-bind:style="{backgroundColor: colorRandom, border: 'solid 3px yellow'}">
            <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
        </li>
        
        <li class="nav-item">
            <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
    </ul>
</template>

<script>
export default {
    name: 'Navegacion',
    data() {
        return {
            mostrarActivo: true,
            colorRandom: "#" + Math.floor(Math.random() * 6777215).toString(16)
        }
    },
}
</script>

<style>
    .active {
        font-weight: bold;
    }
</style>

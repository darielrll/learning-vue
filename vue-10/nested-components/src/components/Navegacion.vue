<template>
    <ul class="nav">        
        <NavegacionItem />
        <NavegacionItem />
        <NavegacionItem />
        <NavegacionItem />
    </ul>
</template>

<script>
import NavegacionItem from './NavegacionItem.vue'

export default {
    name: 'Navegacion',
    components: {
        NavegacionItem
    }
}
</script>

<style>
    .active {
        font-weight: bold;
    }
</style>

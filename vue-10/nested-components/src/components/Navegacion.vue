<template>
    <ul class="nav">        
        <NavegacionItem titulo='Inicio' />
        <NavegacionItem titulo='Acerca' />
        <NavegacionItem titulo='Tienda' />
        <NavegacionItem titulo='Contacto' />
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

<template>
    <ul class="nav">        
        <NavegacionItem v-bind:navegacionData="item" v-for="(item, index) in itemsDeNavegacion" :key="index"/>
        
    </ul>
</template>

<script>
import NavegacionItem from './NavegacionItem.vue'

export default {
    name: 'Navegacion',
    components: {
        NavegacionItem
    },
    data() {
        return {
            itemsDeNavegacion: [
                { titulo: "Inicio", url: '/inicio' },
                { titulo: "Acerca", url: '/acerca' },
                { titulo: "Tienda", url: '/tienda' },
                { titulo: "Contacto", url: '/contacto' },
                { titulo: "Mapa", url: '/mapa' }
            ]
        }
    },
}
</script>

<style>
    .active {
        font-weight: bold;
    }
</style>

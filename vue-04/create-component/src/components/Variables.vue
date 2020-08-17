<template>
    <div>
        <h1>{{libro.titulo}}</h1>
        <h2>{{libro.autor}}</h2>
    </div>
</template>

<script>
export default {
    name: 'Variables',
    data() {
        return {
            libro: {
                autor: 'Umberto Eco',
                titulo: 'Péndulo de Foucault'
            }
        }
    },
}
</script>

<style lang="">
    
</style>
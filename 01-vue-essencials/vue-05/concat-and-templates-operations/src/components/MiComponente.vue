<template>
    <div class='MiComponente'>
        <h1> VUE {{mensajes.texto2}} </h1>
        {{mensajes.texto3}}
        <div v-html="mensajes.texto3"></div>
        <h1> {{mensajes.texto1.toString().toUpperCase()}} </h1>
        <h1> {{mensajes.texto1}} </h1>
        <h1> {{ 1 + 9}} </h1>
        <h1> {{ " hola" + " mundo"}} </h1>
        <h1> {{ mensajes.texto1 + "  ---- >" + mensajes.texto2}} </h1>
    
    </div>
</template>

<script>
export default {
    name: 'MiComponente',
    data() {
        return {
            mensajes:{
                texto1: 'cadena de texto',
                texto2: '.JS',
                texto3: '<h1>Lorem Ipsum </h1> <i>dolor sit amet</i>'
            }
        }
    },
}
</script>

<style>
</style>
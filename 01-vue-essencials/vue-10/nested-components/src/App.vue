<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <Navegacion/>
      </div>
      
      <div class="row">
        <Contenido/>
      </div>
    </div>
  </div>
</template>

<script>
import Navegacion from './components/Navegacion.vue'
import Contenido from './components/Contenido.vue'

export default {
  name: 'App',
  components: {
    Contenido, Navegacion
  }
}
</script>

<style>
</style>

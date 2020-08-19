<template>
  <div id="app">
    <MiComponente/>

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
import MiComponente from './components/MiComponente.vue'
import Navegacion from './components/Navegacion.vue'
import Contenido from './components/Contenido.vue'

export default {
  name: 'App',
  components: {
    Contenido,
    MiComponente, Navegacion
  }
}
</script>

<style>
</style>

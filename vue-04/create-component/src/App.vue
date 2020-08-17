<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MiComponente/>
    <Variables/>
  </div>
</template>

<script>
import MiComponente from './components/MiComponente.vue'
import Variables from './components/Variables.vue'

export default {
  name: 'App',
  components: { 
    MiComponente, Variables
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

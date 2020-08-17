<template>
  <div id="app">
    <div v-for="(x, index) in 10" :key="index">
      <Button></Button>
    </div>
    -------
    <MiComponente />
  </div>
</template>

<script>
import MiComponente from './components/MiComponente.vue'
import Button from './components/Button.vue'

export default {
  name: 'App',
  components: {
    MiComponente, Button
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

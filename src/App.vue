<template>
  <Cabecera />
</template>

<script>
import Cabecera from './components/cabecera.vue'

export default {
  name: 'App',
  components: {
    Cabecera
  }
}
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 25px;
}
</style>

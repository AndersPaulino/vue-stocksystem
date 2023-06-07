<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <StockSystem msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import StockSystem from './components/StockSystem.vue'

export default {
  name: 'app',
  components: {
    StockSystem
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <MyCalculator />
  </div>
</template>

<script>
import MyCalculator from './components/Calculator.vue'

export default {
  name: 'App',
  components: {
   MyCalculator
  }
}
</script>

<style>
body {
  height: 100vh;
  margin: 0;
  padding: 0px;
  width: 100%;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #13293d;
  display: flex;
  height: 100%;
}
</style>

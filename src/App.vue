<template>
  <div id="app">
    <cafe-pdf></cafe-pdf>
  </div>
</template>

<script>
import cafePdf from './components/cafe-pdf.vue'

export default {
  name: 'App',
  components: {
    cafePdf
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

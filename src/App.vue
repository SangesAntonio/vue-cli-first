<template>
  <div id="app">
    
    <titolo/>
    <jumbotron/>
  </div>
</template>

<script>
import titolo from './components/titolo.vue'
import jumbotron from './components/hero.vue'

export default {
  name: 'App',
  components: {
    titolo,
    jumbotron,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

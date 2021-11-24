<template>
  <div id="app">
    <HeaDer/>
   

   
  </div>
</template>

<script>
import HeaDer from './components/Header.vue'

export default {
  name: 'App',
  components: {
    HeaDer
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

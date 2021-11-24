<template>
  <div id="app">
    <HeaDer/>
   
   <main>
     <h3>-->conten goes heare-- </h3>
   </main>

   <FooTer/>
  </div>
</template>

<script>
import HeaDer from './components/Header.vue'
import FooTer from './components/FooTer.vue'


export default {
  name: 'App',
  components: {
    HeaDer,
    FooTer
  }
}
</script>

<style lang="scss">
#app {
 
  main{
    display: flex;
    align-items: center;
    background-color: #000;
    height: 100px;
    h3{
      color: white;
      margin-left: 40px;
    }
  }
}
</style>

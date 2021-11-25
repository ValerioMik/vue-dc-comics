<template>
  <div>
    <Header/>
    <main>
      <Contenuti/>
    </main>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import Contenuti from '@/components/Contenuti.vue'
// import Contenuticard from '@/components/Contenuticard.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Contenuti
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

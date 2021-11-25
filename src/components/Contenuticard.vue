<template>
    <div class="thumbs">
        <img :src="dettagli.thumb" alt="">
        <h2>{{dettagli.series}}</h2>
    </div>
</template>

<script>
export default {
  name: "Contenuticard",
  props:{
    dettagli: Object
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.thumbs{
  width: 16%;
  h2{
    color: white;
  }
  img{
    margin: 20px 10px;
    max-width: 100%;
  }
}
</style>

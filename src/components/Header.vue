<template>
<header>
    <div class="logo">
         <img class="logo" alt="Vue logo" src="../assets\img\dc-logo.png">
    </div>
    <nav>
        <ul >
            <li v-for="link, i in navlogo" :key="i">
                <a :href="link.url">{{link.text}}</a>
            </li>
        </ul>
    </nav>
   
</header>
</template>

<script>
export default {
  name: 'Header',
  data(){
      return{
          navlogo:[
              {
                  text:"characters",
                  url: "#"
                  
              },
              {
                  text:"comics",
                    url: "#"
              },
              {
                  text:"movies",
                    url: "#"
              },
              {
                  text:"tv",
                    url: "#"
              },
              {
                  text:"games",
                    url: "#"
              },
              {
                  text:"videos",
                    url: "#"
              },
              {
                  text:"fans",
                    url: "#"
              },
              {
                  text:"news",
                    url: "#"
              },
              {
                  text:"shop",
                    url: "#"
              },
              {
                text:"collectible",
                  url: "#"
              },
          ]
      }
  }
  
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header{
    justify-content: center;
     align-items: center;
    display: flex;
    li{
        display: inline;
        margin: 0px 10px;
    } 
    a{
        text-decoration: none;
        color: black;
    }
   .logo{
       margin-right: 250px;
   }
}

</style>

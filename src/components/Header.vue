<template>
<header>
    <div class="logo">
         <img class="logo" alt="Vue logo" src="../assets\img\dc-logo.png">
    </div>
    <nav>
        <ul>
            <li><a href="#">characters</a></li>
            <li><a href="#">comics</a></li>
            <li><a href="#">movies</a></li>
            <li><a href="#">tv</a></li>
            <li><a href="#">games</a></li>
            <li><a href="#">collectible</a></li>
            <li><a href="#">videos</a></li>
            <li><a href="#">fans</a></li>
            <li><a href="#">news</a></li>
            <li><a href="#">shop</a></li>
        </ul>
    </nav>
   
</header>
</template>

<script>
export default {
  name: 'HeaDer',
  
}
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

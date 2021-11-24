<template>
<header>
    <div class="logo">
         <img class="logo" alt="Vue logo" src="../assets\img\dc-logo.png">
    </div>
    <nav>
        <ul>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
            <li><a href="#">link</a></li>
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
    display: flex;
    li{
        display: inline;
        margin: 0px 10px;
    } 
    ul{
        align-items: center;

    }
    .logo{
         align-items: center;
    }
}

</style>

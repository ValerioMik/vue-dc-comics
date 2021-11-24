<template>
<footer>
    <div class="info">
        <ul>
            <li><img src="" alt=""></li>
        </ul>

    </div>
    <div class="socials">
        <aside id="sx">
           <div class="linkdisx">
               <h3>
                   DC COMICS
               </h3>
               <ul>
                   <li> <a href=""></a></li>
                   <li><a href=""></a> </li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
               </ul>
               <h3>
                   SHOP
               </h3>
               <ul>
                   <li> <a href=""></a></li>
                   <li><a href=""></a> </li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
               </ul>

           </div>
           <div class="linkdidx">
               <h3>
                   DC
               </h3>
               <ul>
                   <li> <a href=""></a></li>
                   <li><a href=""></a> </li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
               </ul>
               <h3>
                   SITES
               </h3>
               <ul>
                   <li> <a href=""></a></li>
                   <li><a href=""></a> </li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
                   <li> <a href=""></a></li>
               </ul>
           </div>

        </aside>
        <aside id="dx">
           <img class="bigLogo"  src="../assets\img\dc-logo-bg.png">
        </aside>

    </div>

    <div class="iscriviti">

    </div>
    
   
</footer>
</template>

<script>
export default {
  name: 'FooTer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.info{
    background-color: blue;
    height: 100px;
}
.socials{
    background-image: url("../assets/img/footer-bg.jpg");
    height: 280px;
    background-color: black;
}
#sx{
    float: left;

}
#dx{
    float: right;
}
.bigLogo{
    width: 780px;
    height: 280px;
    object-fit: none;

}
.iscriviti{
   height: 300px;
    background-color: grey;
}
.linkdisx{
display: inline-block;
}
.linkdidx{
display: inline-block;
}

</style>

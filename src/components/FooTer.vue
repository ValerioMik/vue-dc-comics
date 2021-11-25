<template>
  <footer>
    <div class="info">
      <ul>
        <li><img src="" alt="" /></li>
      </ul>
    </div>
    <div class="socials">
      <aside id="sx">
        <div class="linkdisx">
          <h3>DC COMICS</h3>
          <ul>
            <li><a href="">characters</a></li>
            <li><a href="">comics</a></li>
            <li><a href="">movies</a></li>
            <li><a href="">tv</a></li>
            <li><a href="">games</a></li>
            <li><a href="">video</a></li>
            <li><a href="">news</a></li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li><a href="">shops dc</a></li>
            <li><a href="">shops dc collections</a></li>
          </ul>
        </div>

        <div class="linkdidx">
          <h3>DC</h3>
          <ul>
            <li><a href="">terme out</a></li>
            <li><a href="">pryvacy policy</a></li>
            <li><a href="">ad choices</a></li>
            <li><a href="">Adversting</a></li>
            <li><a href="">jobs</a></li>
            <li><a href="">subscription</a></li>
            <li><a href="">talent worckscoop</a></li>
          </ul>
          <h3>SITES</h3>
          <ul>
            <li><a href="">dc</a></li>
            <li><a href="">dc magazine</a></li>
            <li><a href="">dc kids</a></li>
            <li><a href="">dc bho</a></li>
            
          </ul>
        </div>
      </aside>
      <aside id="dx">
        <img class="bigLogo" src="../assets\img\dc-logo-bg.png" />
      </aside>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.info {
  background-color: blue;
  height: 100px;
}
.socials {
  background-image: url("../assets/img/footer-bg.jpg");
  height: 280px;
  background-color: black;
}
#sx {
  float: left;
}
#dx {
  float: right;
}
.bigLogo {
  width: 780px;
  height: 280px;
  object-fit: none;
}
.iscriviti {
  height: 130px;
  background-color: grey;
}
.linkdisx {
  height: 40px;
  float: left;
}
.linkdidx {
  float: right;
  height: 40px;
  display: block;
}
h3{
    color: white;
    display: inline-block;
    
}
a{
    color: white;
    text-decoration: none;
}
li{
    list-style: none;
}
</style>

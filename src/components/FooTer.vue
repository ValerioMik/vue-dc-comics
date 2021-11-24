<template>
  <footer>
    <div class="info">
      <ul>
        <li v-for="(card, i) in cards" :key="i">
          <img :src="require(`../assets/img/${card.image}`)" />
        </li>
      </ul>
    </div>
    <div class="socials">
      <aside id="sx">
        <ul>
          <li></li>
        </ul>
      </aside>
      <aside id="dx">
        <img class="bigLogo" src="../assets\img\dc-logo-bg.png" />
      </aside>
    </div>

    <div class="iscriviti"></div>
  </footer>
</template>

<script>
export default {
  name: "FooTer",
  data() {
    return {
      cards: [
        {
          text: "Digital Comics",
          image: "buy-comics-digital-comics.png",
        },
        {
          text: "DC Merchandise",
          image: "buy-comics-merchandise.png",
        },
        {
          text: "Subscriptions",
          image: "buy-comics-subscriptions.png",
        },
        {
          text: "Comic Shop Locator",
          image: "buy-comics-shop-locator.png",
        },
        {
          text: "DC Power Visa",
          image: "buy-dc-power-visa.svg",
        },
      ],
    };
  },
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
  height: 300px;
  background-color: grey;
}
</style>

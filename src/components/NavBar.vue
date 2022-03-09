<template>
  <div class="navbar">
     <ul>
      <li v-for="(items,i) in menu" :key="i"><a :href="items.href"></a>
       <img :src="items.src">
       <span>{{items.text}}</span>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  data() {
    return {
      menu: [
        {
          href: "#",
          src: require("../assets/img/buy-comics-digital-comics.png"),
          text: "digital comics"
        },
        {
          href: "#",
          src: require("../assets/img/buy-comics-merchandise.png"),
          text: "dc merchandise"
        },
        {
          href: "#",
          src: require("../assets/img/buy-comics-subscriptions.png"),
          text: "subscription"
        },
        {
          href: "#",
          src: require("../assets/img/buy-comics-shop-locator.png"),
          text: "comic shop locator"
        },
        {
          href: "#",
          src: require("../assets/img/buy-dc-power-visa.svg"),
          text: "dc power visa"
        },

      ],
    }
  }
}
</script>


<style scoped>

img{
    height: 50px;
}

.navbar{
    height: 150px;
    background-color: rgb(13,106,247);
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 200px;
}

ul{
    display: contents;
    list-style: none;
}

li{
    display: flex;
    align-items: center;
    gap: 15px;
}

span{
    color: white;
    font-size: 13px;
    text-transform: uppercase;
}
</style>

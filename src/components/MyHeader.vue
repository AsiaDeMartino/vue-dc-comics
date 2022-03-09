<template>
  <div class="header">
    <figure>
      <img src="../assets/img/dc-logo.png" alt="">
    </figure>
    <ul>
      <li v-for="(items,i) in menu" :key="i" @click="active(i)" :class="elementoAttivo == i ? 'active' : ''"><a :href="items.href"></a>{{items.text}}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'MyHeader',
  data() {
    return {
      elementoAttivo: 0,
      menu: [
        {
          text: "characters",
          href: "#",
        },
        {
          text: "comics",
          href: "#",
        },
        {
          text: "movies",
          href: "#",
        },
        {
          text: "tv",
          href: "#",
        },
        {
          text: "games",
          href: "#",
        },
        {
          text: "collectibles",
          href: "#",
        },
        {
          text: "videos",
          href: "#",
        },
        {
          text: "fans",
          href: "#",
        },
        {
          text: "news",
          href: "#",
        },
        {
          text: "shop",
          href: "#",
        }
      ],
      active(i) {
        this.elementoAttivo = i;
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img{
  height: 80px;
  width: 80px;
  display: block;

}

.header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100px;
  padding: 0 200px;
}

ul{
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  list-style: none;
  text-transform: uppercase;
  font-size: 12px;
}

li{
  height: 100px;
  display: flex;
  align-items: center;
}

.active{
  color: rgb(13,106,247);
  border-bottom: 2px solid rgb(13,106,247);
}
</style>

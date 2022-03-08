<template>
  <div class="navbar">
     <ul>
      <li><a href="#"></a>
       <img src="../assets/img/buy-comics-digital-comics.png" alt="">
       <span>digital comics</span>
      </li>
      <li><a href="#"></a>
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <span>dc merchandise</span>
      </li>
      <li><a href="#"></a>
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <span>subscription</span>
      </li>
      <li><a href="#"></a>
      <img src="../assets/img/buy-comics-shop-locator.png" alt="">
      <span>comic shop locator</span>
      </li>
      <li><a href="#"></a>
      <img src="../assets/img/buy-dc-power-visa.svg" alt="">
      <span>dc power visa</span>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
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
    justify-content: space-evenly;
    align-items: center;
    padding: 0 100px;
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

<template>
  <div class="header">
    <figure>
      <img src="../assets/img/dc-logo.png" alt="">
    </figure>
    <ul>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
      <li><a href="#"></a>list item</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'MyHeader',
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
  justify-content: space-around;
  align-items: center;
  height: 100px;
}

ul{
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  list-style: none;
  text-transform: uppercase;
  font-size: 12px;
}
</style>

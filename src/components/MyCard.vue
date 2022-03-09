<template>
  <div class="card">
      <figure>
          <img src="" alt="">
      </figure>
      <h1>Titolo</h1>
  </div>
</template>

<script>
export default {
    name: 'MyCard',
}
</script>

<style scoped lang="scss">
.card{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: calc(100% / 7);


    figure{
        height: 100%;
        width: 100%;
        background-color: blue;
        aspect-ratio: 1;
    }

    h1{
        color: white;
    }
}
</style>
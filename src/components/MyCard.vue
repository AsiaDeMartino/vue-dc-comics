<template>
  <div class="card">
      <figure>
          <img :src="items.thumb" alt="">
      </figure>
      <h3>{{items.series}}</h3>
  </div>
</template>

<script>
export default {
    name: 'MyCard',
    props: {
        items: {

        }
    }
}
</script>

<style scoped lang="scss">
.card{
    display: flex;
    flex-direction: column;
    width: calc(100% / 7);
    height: 250px;

    figure{

        width: 100%;
        background-color: blue;
        aspect-ratio: 1;
        flex-shrink: 0;
        overflow: hidden;
    }

    img{
        width: 100%;
    }

    h3{
        padding-top: 10px;
        color: white;
        text-transform: uppercase;
    }
}
</style>
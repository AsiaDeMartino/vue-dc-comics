<template>
  <div class="footer-menu">
    <div class="menu">
        <ul v-for="(items, i) in menu" :key="i">
            <h4>{{items.titolo}}</h4>
            <li v-for="(element, j) in items.contenuto" :key="j">{{element}}</li>
        </ul>
    </div>
    <div class="logo">
        <img src="../assets/img/dc-logo-bg.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterMenu',
  data(){
      return {
          menu: [
              {
                  titolo: "dc comics",
                  contenuto: [
                        "Characters",
                        "Comics",
                        "Movies",
                        "TV",
                        "Games",
                        "Videos",
                        "News"
                  ],
              },
              {
                  titolo: "shop",
                  contenuto: [
                        "Shop DC",
                        "Shop DC Collectibles"
                  ],
              },
              {
                  titolo: "dc",
                  contenuto: [
                        "Terms Of Use",
                        "Privacy policy(New)",
                        "Ad Choices",
                        "Advertising",
                        "Subscriptions",
                        "Talent Workshops",
                        "CPSC Certificate",
                        "Rating",
                        "Shop Help",
                        "Contact Us"
                  ],
              },
              {
                  titolo: "sites",
                  contenuto: [
                        "DC",
                        "MAD Magazine",
                        "DC Kids",
                        "DC Universe",
                        "DC Power Visa",
                  ],
              },
          ]
      }
  }
}
</script>


<style lang="scss" scoped>

img {
    width: 500px;
}

.footer-menu{
    height: 380px;
    display: flex;
    justify-content: space-between;
    color: white;
    background: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;    
    align-items: center; 
    overflow: hidden;
    padding: 0 200px;

    .menu{
    width: 400px;
    height: 100%;
    padding: 30px 0;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    flex-wrap: wrap;
    }

    ul{
    display: flex;
    flex-direction: column;
    row-gap: 8px;
    list-style: none;
    }

    h4{
    margin-bottom: 10px;
    margin-top: 20px;
    text-transform: uppercase;
    }

    li{
    font-size: 12px;
    color: rgb(186, 183, 183);

        &:hover{
        color: white;
        }
    }   
}

</style>

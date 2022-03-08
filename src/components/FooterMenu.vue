<template>
  <div class="footer-menu">
    <div class="menu">
        <ul>
            <h5>DC COMICS</h5>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
        </ul>
        <ul>
            <h5>SHOP</h5>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
        </ul>
        <ul>
            <h5>DC</h5>
            <li>Terms Of Use</li>
            <li>Privacy policy (New)</li>
            <li>Ad Choices</li>
            <li>Advertaising</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Rating</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
        </ul>
        <ul>
            <h5>SITES</h5>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
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
}
</script>


<style scoped>

img {
    width: 500px;
}

.footer-menu{
    height: 380px;
    display: flex;
    justify-content: space-evenly;
    color: white;
    background: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;    
    align-items: center; 
    overflow: hidden;
}

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

h5{
margin-bottom: 10px;
margin-top: 20px;
}

li{
    font-size: 12px;
    color: rgb(186, 183, 183);
}

li:hover{
    color: white;
}

</style>

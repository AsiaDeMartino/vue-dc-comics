<template>
  <div class="footer">
    <div>
        <button type="button" class="bottone">sign up now!</button>
    </div>
    <div class="social">
        <h2>follow us</h2>
        <ul>
            <li><a href="#"></a>
                <img src="../assets/img/footer-facebook.png" alt="">
            </li>
            <li><a href="#"></a>
                <img src="../assets/img/footer-twitter.png" alt="">
            </li>
            <li><a href="#"></a>
                <img src="../assets/img/footer-youtube.png" alt="">
            </li>
            <li><a href="#"></a>
                <img src="../assets/img/footer-pinterest.png" alt="">
            </li>
            <li><a href="#"></a>
                <img src="../assets/img/footer-periscope.png" alt="">
            </li>
        </ul>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'MyFooter',
}
</script>

<style scoped>
.footer{
    height: 110px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 200px;
    background-color: rgb(36,36,36);
}

img{
    height: 30px;
    display: block;
}

.social{
    display: flex;
    align-items: center;
    gap: 20px;
    color: rgb(13,106,247);
    text-transform: uppercase;
}


ul{
    list-style: none;
    display: contents;
}

.bottone{
    height: 50px;
    width: 150px;
    border: 3px solid rgb(13,106,247);
    text-transform: uppercase;
    font-size: 16px;
    color: white;
    background-color: transparent;
}
</style>

<template>
  <div id="app">
   <MyHeader />
   <MyMain />
   <NavBar />
   <FooterMenu />
   <MyFooter />
    
  </div>
</template>

<script>
  import MyHeader from './components/MyHeader.vue'
  import MyMain from './components/MyMain.vue'
  import NavBar from './components/NavBar.vue'
  import FooterMenu from './components/FooterMenu.vue'
  import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    NavBar,
    FooterMenu,
    MyFooter,
    
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Dosis', sans-serif;
}

@import url('https://fonts.googleapis.com/css2?family=Dosis:wght@200;400;600&display=swap');


</style>

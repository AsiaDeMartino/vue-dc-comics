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
  import MyMain from '/src/components/MyMain.vue'
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

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


</style>

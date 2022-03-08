<template>
  <div id="app">
   <MyHeader />
   <MyMain />
   <NavBar />
    
  </div>
</template>

<script>
  import MyHeader from './components/MyHeader.vue'
  import MyMain from '/src/components/MyMain.vue'
  import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    NavBar,
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


#app {
  color: black;
}
</style>

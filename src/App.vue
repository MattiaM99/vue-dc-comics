<template>
  <div id="app">
    <Header/>
    <Jumbotron/>
    <Main/>
    <Merch/>
    <Footer/> 
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue';
import Main from './components/Main.vue'
import Merch from './components/Merch.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Main,
    Merch,
    Footer
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>

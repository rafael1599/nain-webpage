<template>
  <Cabecera msg="Header" />
  <Home msg="Home page"/>
  <FlashSale msg="Flash sale"/>
</template>

<script>
import Home from './pages/Home.vue'
import Cabecera from './components/Cabecera.vue'
import FlashSale from './pages/FlashSale.vue'

export default {
  name: 'App',
  components: {
    Home,
    FlashSale,
    Cabecera,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

@import './assets/css/style.css';
@import './assets/css/header.css';

</style>

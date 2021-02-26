<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <carousel Items="itemList"/>
  </div>
</template>

<script>
import Carousel from './components/Carousel.vue'

export default {
  name: 'App',
  itemList:[{
    id:1,
    Title:'amir'
  }],
  components: {
   Carousel
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
  margin-top: 60px;
}
</style>

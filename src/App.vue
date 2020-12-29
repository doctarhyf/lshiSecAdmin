<template>
  <div id="app">
    <img width="100px" alt="Vue logo" src="./assets/flame.png">
    <!-- <HelloWorld msg="🤣Cool Welcome to Your Vue.js App"/> -->
    <LshiSec name="my name new components 😁😝"></LshiSec>

  </div>
</template>

<script>
import LshiSec from './components/LshiSec.vue'
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    LshiSec
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

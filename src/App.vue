<template>
  <div id="app">
    <img width="100px"  alt="Vue logo" src="./assets/flame.png">
    <!-- <HelloWorld msg="🤣Cool Welcome to Your Vue.js App"/> -->
    <LshiSec name="my name new components 😁😝"></LshiSec>
    
  </div>
</template>

<script>
import LshiSec from './components/LshiSec.vue'
//import HelloWorld from './components/HelloWorld.vue'

import UIkit from 'uikit';
import Icons from 'uikit/dist/js/uikit-icons';
UIkit.use(Icons);


export default {
  name: 'App',
  components: {
    LshiSec
  }
}
</script>






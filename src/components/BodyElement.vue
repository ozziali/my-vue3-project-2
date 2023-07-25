<template>
  <div class="body-div">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Image />
  </div>
</template>

<script>
// const Image = require('../../assets/images/pic1.png'.default)

import HelloWorld from './headerComponents/HelloWorld.vue'
  export default {
    name: "BodyElement",
    data () {
    
    },
    components: {
      HelloWorld,
      Image
    }
  }
</script>

<style  scoped>
.body-div{
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
</style>
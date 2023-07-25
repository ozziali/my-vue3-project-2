<template>
  <div class="body-div">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './headerComponents/HelloWorld.vue'
  export default {
    name: "BodyElement",
    components: {
      HelloWorld
    }
  }
</script>

<style  scoped>
.body-div{
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
</style>
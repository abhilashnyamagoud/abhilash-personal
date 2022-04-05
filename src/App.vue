<template>
    <Navbar/>
  <router-view/>
</template>

<script>
import Navbar from '../src/components/Navbar/Navbar.vue'
    export default {
      components:{
        Navbar
      }
        
    }

</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  background: lavender;
}


</style>

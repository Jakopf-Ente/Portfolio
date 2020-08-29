<template>

<b-container fluid>
  <div id="app">
      <navbar/>
      
      <router-view>
      
      <home/>
      
      </router-view>
      
      <futter/>
  
  </div>
  
</b-container>

</template>

<style>

</style>

<script>
import navbar from "@/Navbar/nav.vue"
import futter from "@/Box/futter.vue"
import home from "@/views/Home.vue"

export default {
  name: 'Index',
  components: {
    navbar,
    futter,
    home,
  },
}



</script>

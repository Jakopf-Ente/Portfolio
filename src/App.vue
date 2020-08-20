<template>
  <div id="app">
      <navbar/>
      <boxleft/>
      <boxright/>

      <router-view/>
  </div>
</template>

<style>

</style>

<script>
import navbar from "@/Navbar/nav.vue"
import boxleft from "@/Box/boxleft.vue"
import boxright from "@/Box/boxright.vue"

export default {
  name: 'Index',
  components: {
    navbar,
    boxleft,
    boxright,
  },
}



</script>

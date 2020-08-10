<template>
  <div id="app">
      <navbar/>
      <router-view/>
  </div>
</template>

<style>

</style>

<script>
import navbar from "@/Navbar/nav.vue"

export default {
  name: 'Index',
  components: {
    navbar,
  },
}

</script>

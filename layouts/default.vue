<template>
  <div class="container" lazy-background="/back3.gif">
    <div class="content">
      <Navbar class="absolute" />
      <Nuxt />
    </div>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
export default {
  components: {
    Navbar
  }
}
</script>

<style >
.container {
  top: 5%;
  min-height: 100vh;
  min-width: 100%;
  display: flex;
  text-align: left;
  background-size: cover;
  background-attachment: fixed;
  background-position: center center;
  padding-bottom: 0;
  box-sizing: content-box;
}
.content {
  min-width: 100%;
}
</style>

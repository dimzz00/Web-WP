<template>
  <div class="container2">
    <div class="text-error">
      <h1 style="color:white">
        This Page Is Under Development
      </h1>
      <nuxt-link
        to="/about"
        class="button--green"
      >
        Back
      </nuxt-link>
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  layout: 'tes1',
  components: {
  }
}
</script>

<style scoped>
.container2 {
  background:rgba(0, 0, 0, 0.5);
  margin: auto;
  min-height: 100vh;
  display: flex;
  align-items: left;
  text-align: center;
}
.text-error {
  color: white;
  margin: auto;
}
</style>

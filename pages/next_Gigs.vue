<template>
  <div class="container2">
    <div>
      <h1 class="title_NG">
        Coming soon
      </h1>
      <h2 class="subtitle_NG">
        "Next Update"
      </h2>
      <!-- <div class="links">
        <nuxt-link
          to="/about"
          class="button--green"
        >
          About
        </nuxt-link>
        <nuxt-link
          to="media"
          class="button--grey"
        >
          Media
        </nuxt-link>
      </div> -->
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  components: {
  }
}
</script>

<style>
.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  align-items: center;
    background-image: url('/back4.png');
    background-size: cover;
    background-attachment: fixed;
}

.title_NG {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: white;
  letter-spacing: 1px;
  position: fixed;
  left: 40%;
  top:30%;
}

.subtitle_NG {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
  position: fixed;
  left: 40%;
}

.links {
  padding-top: 15px;
  position: fixed;
  top:40%;
  left:60%;
}
</style>

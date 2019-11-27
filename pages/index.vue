<template>
  <div class="container2">
    <div>
      <div class="content">
         <h1 class="title">
        Weaboo. Project.
      </h1>
      <p class="subtitle">
        #MakeWeabooGreatAgain
      </p>
      </div>
      <div class="links">
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
      </div>
       <!-- <div class="linksMedia">
       <a class="button--green" href="https://www.instagram.com/weabooproject/"><i class="fab fa-youtube"></i><strong>IG</strong> </a>
        <a class="button--grey" href="http://youtube.com"> <strong>YT</strong></a>
      </div> -->
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  layout: 'blabla',
  components: {
  }
}
</script>

<style scoped>
.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  align-items: left;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-weight: bold;
  font-size: 100px;
  color: white;
  letter-spacing: 1px;
  left: 15%;
  top: 26%;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
  left: 18%;
}

.links {
  padding-top: 15px;
  position: fixed;
  top:40%;
  left:5.5%;
}
.linksMedia {
  padding-top: 15px;
  position: fixed;
  top:10%;
  left:83%;
  display: flex;
}

.content {
  margin-top: 10%;
  margin-left: 10%;
}
</style>

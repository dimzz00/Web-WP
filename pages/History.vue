<template>
   <div class="container">
   <div class="content">
       <p class="title"><strong>Sejarah</strong></p>
       <p class="subtitle">Awalnya terbentuk hanya untuk menjadi project cover seperti AniSongCollabo.</p>
       <p class="subtitle">Karena terkendala peralatan, fokus dirubah menjadi band seutuhnya yang tampil diacara festival jejepangan BDG</p>

  </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  components: {
    // Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content:center;
  align-items: center;
  text-align:center;
  background-image: url(punggung.jpg);
  background-size:auto;
  background-repeat: no-repeat;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color:white;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color:white;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

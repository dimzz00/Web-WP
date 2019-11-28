<template>
   <div class="container2">
   <div class="content">
       <p class="title"><strong>Sejarah perwibuaan</strong></p>
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

<style scoped>
.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content:center;
  text-align:center;
  background-image: url('/punggung.png');
  background-size:cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 85px;
  color:white;
  letter-spacing: 1px;
  padding-top: 10%;
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

<template>
   <div class="container2">
   <div class="content">
       <p class="title"><strong style="color: turquoise">Sejarah</strong><br><strong style="color: pink">Perwibuan</strong></p>
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
  display:block;
  justify-content:center;
  text-align:left;
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
  font-size: 80px;
  color:white;
  letter-spacing: 1px;
  padding-top: 5%;
  padding-left: 10%;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color:white;
  word-spacing: 5px;
  padding-bottom: 10px;
  padding-left: 10%;
  padding-right: 10%;
}

.links {
  padding-top: 15px;
}
.content{
  margin-top: 0%;
}

/* tablet  (xs) */
@media (max-width: 769px){
  .subtitle{
    font-size: 20px;
  }
  .title{
    font-size: 60px;
    padding-right: 5%;
  }
  }
</style>

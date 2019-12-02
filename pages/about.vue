<template>
   <div class="container2">
      <div class="content">
        <p class="title">Weaboo.<br>Project.</p><br>
        <p class="subtitle">Weaboo Project sebuah band dari bojongsoang yang awalnya tampil di event jejepangan, namun sekarang mencoba untuk tampil lebih umum selain jejepangan saja.</p>
        <p class="subtitle">Selama 2 tahun terakhir, Weaboo Project sudah bermain dibanyak festival jejepangan dibandung dan beberapa kali di jakarta.</p>
        <img src="" alt="">
        <p class="subtitle">Weaboo project memang tidak terlalu sering untuk tampil festival jepang dikarenakan masing-masing personil juga memiliki kehidupan normal.</p>
        <p class="subtitle">Karena Weaboo Project dibuat untuk menampung para "WIBU" yang menyukai musik untuk berproject dalam satu kesatuan perwibuan yang lebih baik!. </p>
        </div>
        <!-- <p class="subtitle1">#MakeWibuGreatAgain </p> -->
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
  top: 5%;
  min-height: 100vh;
  display: flex;
  text-align: left;
  background-image: url('/back3.png');
  background-size: cover;
  background-attachment: fixed;
  padding-bottom: 10%;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 85px;
  color: white;
  letter-spacing: 1px;
  padding-top: 0%;
  padding-left: 10%;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
  padding-left: 10%;
  padding-right: 10%;
}
.subtitle1 {
  font-weight: 300;
  font-size: 15px;
  color: white;
  word-spacing: 5px;
  float: right;
  padding-top: 70%;
  padding-right: 10%;
  display: flex;
  position:static;
}
.content{
  top:5%;
}
.links {
  padding-top: 15px;
}

@media (max-width: 769px){
  .subtitle{
    font-size: 20px;
  }
  .title{
    font-size: 66px;
    padding-right: 5%;
  }
  }
</style>

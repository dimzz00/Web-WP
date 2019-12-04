<template>
   <div class="container2">
      <div class="content">
        <p class="title"><strong style="color: turquoise">Weaboo.</strong><br><strong style="color: pink">Project.</strong></p><br>
        <p class="subtitle"><strong style="color: turquoise">Weaboo Project </strong>sebuah band dari bojongsoang yang awalnya tampil di event jejepangan, namun sekarang mencoba untuk tampil lebih umum selain jejepangan saja.</p>
        <p class="subtitle">Selama 2 tahun terakhir, <strong style="color: pink">Weaboo Project </strong> sudah bermain dibanyak festival jejepangan dibandung dan beberapa kali di jakarta.</p>
             <img src="/kon2017-1.jpg" class="poto">
             <p class="subtitle1">Panggung pertama Weaboo Project.</p>
             <img src="/kon2017-2.jpg" class="poto">
             <p class="subtitle1">Formasi pertama Weaboo Project.</p>
        <p class="subtitle3"><strong style="color: turquoise">Weaboo Project </strong> memang tidak terlalu sering untuk tampil festival jepang dikarenakan masing-masing personil juga memiliki kehidupan normal.</p>
        <p class="subtitle">Karena <strong style="color: pink">Weaboo Project </strong> dibuat untuk menampung para "WIBU" yang menyukai musik untuk berproject dalam satu kesatuan perwibuan yang lebih baik!. </p>
             <img src="/eni2019-1.jpg" class="poto">
            <p class="subtitle1">Lastest Gigs</p>
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
  font-size: 80px;
  color:white;
  letter-spacing: 1px;
  padding-top: 5%;
  padding-left: 10%;
  padding-bottom: 0%;
}
.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-top: 0%;
  padding-bottom: 15px;
  padding-left: 10%;
  padding-right: 10%;
}
.subtitle1 {
  font-weight: 300;
  font-size: 15px;
  color: white;
  word-spacing: 5px;
 padding-top: 0%;
  justify-content: center;
    align-items: center;
    text-align: center;
}
.subtitle3 {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-top: 5%;
  padding-bottom: 15px;
  padding-left: 10%;
  padding-right: 10%;
}
.content{
  top:0%;
}
.links {
  padding-top: 15px;
}
.poto{
  width: 50%;
  height: 50%;
  display: flex;
   justify-content: center;
  align-items: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
  padding-top: 3%;
  padding-bottom: 0%;
}
.poto:hover {
  -ms-transform: scale(1.5); /* IE 9 */
  -webkit-transform: scale(1.5); /* Safari 3-8 */
  transform: scale(1.2);
}

@media (max-width: 769px){
  .subtitle{
    font-size: 20px;
  }
   .subtitle3{
    font-size: 20px;
  }
  .title{
    font-size: 60px;
    padding-right: 5%;
    bottom: 0%;
  }
  .poto{
  width: auto;
  height: auto;
  display: flex;
   justify-content: center;
  align-items: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
  padding-top: 3%;
  padding-bottom: 0%;
  padding-left: 10%;
  padding-right: 10%;
  }
  .poto:hover {
  -ms-transform: scale(1.5); /* IE 9 */
  -webkit-transform: scale(1.5); /* Safari 3-8 */
  transform: scale(1.0);
}

  }
</style>

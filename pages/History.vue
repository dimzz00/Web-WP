<template>
   <div class="container2">
   <div class="content" style="clear:both;">
     <marquee behavior="alternate" scrollamount="10" direction="right" style="padding-bottom: 5%">
              <p class="title"><strong style="color: turquoise">Sejarah</strong><br><strong style="color: pink">Perwibuan</strong></p>
     </marquee>
       <p class="subtitle">Awalnya terbentuk hanya untuk menjadi project cover seperti AniSongCollabo.</p>
       <p class="subtitle">Karena terkendala peralatan, fokus dirubah menjadi band seutuhnya yang tampil diacara festival jejepangan BDG</p>
  <div class="timeline">
    <ul>
      <li>
        <div class="content1">
          <h3 >Konbanwa Festival 2017</h3>
          <img src="kon2017-1.jpg" style="opacity:1">
          <p>Konbanwa Fest. adalah panggung pertama Weaboo Project dengan formasi pertama.</p>
        </div>
        <div class="time">
          <h4>16 Dec 2017</h4>
        </div>
      </li>
      <li>
        <div class="content1">
          <h3>Pre Bandung Wonderland 2018</h3>
          <img src="BW.jpg" style="opacity:1">
          <p>Bandung Wonderland adalah panggung kedua Weaboo Project yang mencoba konsep "wibu tradisonal dengan menggunakan batik" dan formasi sekarang berawal dari event ini.</p>
        </div>
        <div class="time">
          <h4>4 March 2018</h4>
        </div>
      </li>
      <li>
        <div class="content1">
          <h3>Sashimi X Widyatama</h3>
          <img src="sashimi.jpg" style="opacity:1">
          <p>#SashimiWidyatama merupakan panggung ketiga Weaboo Project setelah lolos audisi untuk tampil diacara utama.</p>
        </div>
        <div class="time">
          <h4>28 Apr 2018</h4>
        </div>
      </li>
      <li>
        <div class="content1">
          <h3>Ennichisai Blok M 2018</h3>
          <img src="eni2018.jpg" style="opacity:1">
          <p>Untuk pertama kalinya Weaboo Project mencoba peruntungan tampil diluar jakarta di Chika Stage Ennichisai Day 2 setelah lolos audisi yang diadakan Ennichisai.</p>
          <p style="font-size:10px">Photo from Facebook Ennichisai</p>
        </div>
        <div class="time">
          <h4>1 Jul 2018</h4>
        </div>
      </li>
       <li>
        <div class="content1">
          <h3>Yamaton Damashii XIII</h3>
          <img src="sementara.jpg" style="opacity:1">
          <p>Yamaton Damashii XIII adalah panggung kelima Weaboo Project.</p>
          <p style="font-size:10px">moonmaap ga ada poto pas manggung.</p>
        </div>
        <div class="time">
          <h4>23 Sep 2018</h4>
        </div>
      </li>
      <li>
        <div class="content1">
          <h3>Fesbukan Unpad 2018</h3>
          <img src="Fesbukan.jpg" style="opacity:1">
        <p>Fesbukan Unpad 2018 merupakan panggung keenam Weaboo Project.</p>
        </div>
        <div class="time">
          <h4>7 Oct2018</h4>
        </div>
      </li>
       <li>
        <div class="content1">
          <h3>Bandung Wundurland </h3>
          <img src="bwmain.jpg" style="opacity:1">
        <p>Bandung Wundurland 2018 adalah panggung ketujuh Weaboo Project dengan membawakan lagu fhana-Aozora no Rhapsody.</p>
        <p style="font-size:10px">moonmaap ga ada poto pas manggung.</p>
        </div>
        <div class="time">
          <h4>4 Nov 2018</h4>
        </div>
      </li>
      <li>
        <div class="content1">
          <h3>Japanzuki Show 14</h3>
          <img src="upi.jpg" style="opacity:1">
        <p>Weaboo Project tampil di Japanzuki Show 14 2019 sebagai juara kedua audisi yang diadakan oleh Japanzuki Show 14.</p>
        </div>
        <div class="time">
          <h4>28 Apr 2019</h4>
        </div>
      </li>
      <li>
        <div class="content1">
          <h3>Ennichisai Blok M 2019</h3>
          <img src="eni2019-1.jpg" style="opacity:1">
        <p>Untuk kedua kalinya Weaboo Project tampil di Chika Stage Ennichisai di Day 1.</p>
        <p style="font-size:10px">Photo from Facebook Ennichisai.</p>
        </div>
        <div class="time">
          <h4>22 Jun 2019</h4>
        </div>
      </li>
    </ul>
    <div style="clear:both;"></div>
  </div>
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
  background-image: url('/punggung.GIF');
  background-size:cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center center;
}
.blurr {
   background: rgb(135, 206, 235, 0.3);
  filter:blur(5);
  width: 95%;
  position: static;;
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
.content{
  padding-bottom:20px;
  margin-top: 0%;
}
.content1{
  margin-top: 5%;
  background-color: #eee3e7;
  opacity: 1;
  border-radius: 3%;
  padding: 5% 5% 5% 5%;
}
.content1:hover{
 transform: scale(1.2);
}
div.content1 p{
  font-weight: bold;
  color:black;
}
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,500,600');
body{
  padding:0;
  margin:0;
  font-family: 'Montserrat', sans-serif;
}
h1{
  font-size:60px;
  text-align:center;
}
.timeline{
  position:relative;
  margin:50px auto;
  padding:40px 0;
  width:1000px;
  box-sizing:border-box;
}
.timeline:before{
  content:'';
  position:absolute;
  left:50%;
  width:2px;
  height:100%;
  background:#c5c5c5;
}
.timeline ul{
  padding:0;
  margin:0;
}
.timeline ul li{
  list-style:none;
  position:relative;
  width:50%;
  padding:20px 40px;
  box-sizing:border-box;
}
.timeline ul li:nth-child(odd){
  float:left;
  text-align:right;
  clear:both;
}
.timeline ul li:nth-child(even){
  float:right;
  text-align:left;
  clear:both;
}
.timeline ul li:nth-child(odd):before
{
  content:'';
  position:absolute;
  width:10px;
  height:10px;
  top:24px;
  right:-6px;
  background:black;
  border-radius:50%;
  box-shadow:0 0 0 3px pink;
}
.timeline ul li:nth-child(even):before
{
  content:'';
  position:absolute;
  width:10px;
  height:10px;
  top:24px;
  left:-4px;
  background:black;
  border-radius:50%;
  box-shadow:0 0 0 3px pink;
}
.timeline ul li h3{
  padding:0;
  margin:0;
  color:rgb(red, rgb(100, 100, 100), blue);
  font-weight:800;
  font-size: 25px;
}
.timeline ul li p{
  margin:10px 0 0;
  padding:0;
}
.timeline ul li .time h4{
  margin:0;
  padding:0;
  font-size:14px;
  font-weight: 700;
}
.timeline ul li:nth-child(odd) .time
{
  position:absolute;
  top:12px;
  right:-165px;
  margin:0;
  padding:8px 16px;
  background:pink;
  color:black;
  border-radius:18px;
  box-shadow:0 0 0 3px palevioletred;
}
.timeline ul li:nth-child(even) .time
{
  position:absolute;
  top:12px;
  left:-165px;
  margin:0;
  padding:8px 16px;
  background:pink;
  color:black;
  border-radius:18px;
  box-shadow:0 0 0 3px palevioletred;
}
@media(max-width:1000px)
{
  .timeline{
    width:100%;
  }
}
@media(max-width:767px){
  .timeline{
    width:100%;
    padding-bottom:0;
  }
  h1{
    font-size:40px;
    text-align:center;
  }
  .timeline:before{
    left:20px;
    height:100%;
  }
  .timeline ul li:nth-child(odd),
  .timeline ul li:nth-child(even)
  {
    width:100%;
    text-align:left;
    padding-left:50px;
    padding-bottom:50px;
  }
  .timeline ul li:nth-child(odd):before,
  .timeline ul li:nth-child(even):before
  {
    top:-18px;
    left:16px;
  }
  .timeline ul li:nth-child(odd) .time,
  .timeline ul li:nth-child(even) .time{
    top:-30px;
    left:50px;
    right:inherit;
  }
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

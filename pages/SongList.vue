<template>
  <div class="container2">
    <div class="content">
      <p class="title">
        <strong style="color: turquoise">Song</strong><strong style="color: pink">List</strong>
      </p>
      <ol>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=Ayjj473UPpU">
            <span style="color: turquoise">LiSA</span> - <span style="color: pink">Catch The Moment</span></a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=Pe9YewTA-y8">
            <span style="color: pink">Babymetal</span> - <span style="color: turquoise">Megitsune</span></a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=Pe9YewTA-y8">
            <span style="color: turquoise">Babymetal</span> - <span style="color: pink">Akatsuki</span></a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle">
            <span style="color: pink">Sayuri</span> - <span style="color: turquoise">Heikousen</span></a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle">
            <span style="color: turquoise">fhàna</span> - <span style="color: pink">Aozora No Rhapsody</span></a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=QF6U5r_qcOc">
            <span style="color: pink">Machiko</span> - <span style="color: turquoise">Tomorrow</span></a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=pU66822dz0M">
            <span style="color: turquoise">ManamiNumakura</span> - <span style="color: pink">Climber's High</span></a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=qg973PSo0NM">blom</a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=qg973PSo0NM">garap </a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=qg973PSo0NM">lagu</a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=qg973PSo0NM">yang</a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=qg973PSo0NM">laen</a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=qg973PSo0NM">lagi</a><br>
        </li>
        <li class="subtitle">
          <a class="subtitle" href="https://www.youtube.com/watch?v=qg973PSo0NM">sibuk</a><br>
        </li>
      </ol>
      <!-- <audio src="/05 Akatsuki.m4a" controls>
        <p>Fallback content goes here.</p>
      </audio> -->
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
  justify-content: center;
  background-image: url('/back2.GIF');
  background-size: cover;
  background-attachment: fixed;
  padding-bottom: 10%;
  top: 0%;
  padding-left: 5%;
    padding-right: 5%;
  background-position: center center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    font-weight: 300;
    font-size: 90px;
    color:white;
    letter-spacing: 1px;
    justify-content: center;
    align-items: center;
    text-align: center;
    top: 0%;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
  justify-content: center;
    align-items: center;
    text-align: center;
}

.links {
  padding-top: 15px;
}
.content{
    color: white;
    margin-top:5%;
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

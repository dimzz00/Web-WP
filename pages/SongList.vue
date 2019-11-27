<template>
    <div class="container">
     <div class="content">
        <p class="title">SongList</p>
        <ol>
       <li class="subtitle"> <a class="subtitle" href="https://www.youtube.com/watch?v=Ayjj473UPpU">lisa</a><br></li>
        <li class="subtitle"> <a class="subtitle" href="https://www.youtube.com/watch?v=Pe9YewTA-y8">babymetal</a><br></li>
        <li class="subtitle"> <a class="subtitle">sayuri</a><br></li>
        <li class="subtitle"> <a class="subtitle">fhana</a><br></li>
        <li class="subtitle"> <a class="subtitle" href="https://www.youtube.com/watch?v=QF6U5r_qcOc">machiko</a><br></li>
        <li class="subtitle"> <a class="subtitle" href="https://www.youtube.com/watch?v=pU66822dz0M">manami numakura</a><br></li>
        </ol>
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
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  text-align: center;
   background-image: url('/punggung.png');
    background-size: cover;
    background-attachment: fixed;
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
    margin-top:10%;
}
</style>

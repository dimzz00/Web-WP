<template>
    <div class="container">
     <div class="content">
        <p class="title">samID</p>
        <p class="subtitle">Setengah Wibu setengah WIBU</p>
        <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/videoseries?list=PLwsQ6fwvIIxO35gnAn7ImIbtjt32g0-Cg"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
        </iframe>
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
  align-items: center;
  text-align: center;
   background-image: url('/samid.png');
    background-size: cover;
    background-attachment: fixed;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    font-weight: 300;
    font-size: 100px;
    color: white;
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
}
</style>

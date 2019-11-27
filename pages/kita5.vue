<template>
<div class="container2">
     <div class="content">
        <p class="title">Gio</p>
        <p class="subtitle">Setengah Wibu setengah Normal</p>
         <iframe class="yt" width="cover" height="cover" src="https://www.youtube.com/embed/videoseries?list=PLw-LNUHX2AEj9VutIAJb2g_PTDGg7ddTI">
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
.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
   background-image: url('/Gio.jpg');
    background-size: cover;
    background-attachment: fixed;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    font-weight: 300;
    font-size: 100px;
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
}
</style>

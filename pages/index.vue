<template>
  <div class="container2">
    <div>
      <div class="content">
         <h1 class="title">
        <strong style="color: turquoise">Weaboo.</strong> <strong style="color: pink">Project.</strong>
      </h1>
      <p class="subtitle">
        <strong style="color: turquoise">#MakeWeaboo</strong><strong style="color: pink">GreatAgain</strong>
      </p>
      </div>
      <div class="links">
        <nuxt-link
          to="/about"
          class="button--green"
        >
          About
        </nuxt-link>
        <nuxt-link
          to="media"
          class="button--grey"
        >
          Media
        </nuxt-link>
      </div>
      <!-- <div class="linksMedia">
        <p>Keep In Touch Here!</p><br>
        <a href="https://www.youtube.com/channel/UCE66EFZGyV7Jbf1yMO4QwNw" class="button--green">Youtube</a>
        <a href="https://www.instagram.com/weabooproject/" class="button--green">Instagram</a>
      </div> -->
       <!-- <div class="linksMedia">
       <a class="button--green" href="https://www.instagram.com/weabooproject/"><i class="fab fa-youtube"></i><strong>IG</strong> </a>
        <a class="button--grey" href="http://youtube.com"> <strong>YT</strong></a>
      </div> -->
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  layout: 'blabla',
  components: {
  }
}
</script>

<style scoped>
.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  align-items: left;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-weight: bold;
  font-size: 85px;
  color: white;
  letter-spacing: 1px;
  left: 15%;
  top: 26%;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
  left: 18%;
}

.links {
  padding-top: 15px;
  position: fixed;
  top:60%;
  padding-left:7%;
}
.linksMedia {
  position: fixed;
  justify-content: center;
  align-items: center;
  display: flex;
  left: 35%;
  top: %;
}

.content {
  margin-top: 10%;
  margin-left: 10%;
  display: block;
  position: fixed;
}

@media (max-width: 769px){
  .content {
    margin-top : 10%;
    display: block;
  }
  .subtitle{
    font-size: 20px;
  }
  .title{
    font-size: 60px;
    padding-right: 0%;
    top: 0%;
  }
  .links {
  padding-top: 15px;
  position: fixed;
  top:60%;
  padding-left:10%;
  padding-bottom: 0%;
  display: block;
  -ms-accelerator: true;
}
  }
  @media (min-width: 769px) and (max-width: 1023px) {
     .content {
    margin-top : 20%;
  }
    .subtitle{
    font-size: 20px;
  }
  .title{
    font-size: 70px;
    padding-right: 5%;
  }
  .links {
  padding-top: 15px;
  position: fixed;
  top:60%;
  padding-left:10%;
}
  }
</style>

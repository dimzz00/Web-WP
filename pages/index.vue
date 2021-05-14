<template>
  <div class="container2">
    <div class="content">
      <h1 class="title">
        <strong style="color: turquoise">Weaboo</strong><br><strong style="color: pink">Project</strong>
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
        to="coba"
        class="button--grey"
      >
        Media
      </nuxt-link>
    </div>
  </div>
</template>

<script>

export default {
  layout: 'blabla'
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
  padding-left:35%;
  justify-content: center;
    align-items: center;
    text-align: center;
}
.content {
  margin-top: 10%;
  margin-left: 10%;
  display: block;
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
  padding: 10%;
  display: flex;
  justify-content: center;
    align-items: center;
    text-align: center;
  display: block;
  -ms-accelerator: true;
}
  }
  @media (min-width: 769px) and (max-width: 1023px) {
     .content {
       padding: 0;
    margin-top: 10%;;
  }
    .subtitle{
    font-size: 20px;
  }
  .title{
    font-size: 60px;
    padding-right: 5%;
  }
  .links {
  padding-top: 15px;
  position: fixed;
  top:60%;
  padding-left:35%;
}
  }
</style>

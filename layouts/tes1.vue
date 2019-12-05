<template>
<div class="dasar">
    <video autoplay muted loop class="videoBG">
    <source src="/back.mp4" type="video/mp4">
    </video>
    <div class="container2">
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
  </div>
</div>
</template>
<style scoped>
.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  align-items: left;
}
.dasar{
    justify-content: center;
    align-items: center;
    text-align: center;
}
.dasar video{
    position: absolute;
    top:0;
    left:0;
    object-fit: cover;
     width: 100%;
     height: 100%;
}
.content{
    position: fixed;
    justify-content: center;
    align-content: center;
    text-align: center;
    padding-left: 10%;
    padding-top: 10%;
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 100px;
  color: turquoise;
  letter-spacing: 1px;
  justify-content: center;
    align-content: center;
    text-align: center;
}
.subtitle {
  font-weight: 100;
  font-size: 30px;
  word-spacing: 5px;
  padding-bottom: 15px;
  left: 18%;
}
.videoBG{
    position: fixed;
    right: 0;
    top: 0;
    bottom: 0;
}
.links {
  padding-top: 15px;
  position: fixed;
  top:60%;
  padding-left:7%;
  justify-content: center;
    align-items: center;
    text-align: center;
}
.content {
  margin-top: 10%;
  margin-left: 10%;
  display: block;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid turquoise;
  color: pink;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #35495e;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid pink;
  color:turquoise;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
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
  padding-left: 10%;
  display: flex;
  justify-content: center;
    align-items: center;
    text-align: center;
  display: block;
  -ms-accelerator: true;
}
.button--green {
  display: inline-block;
  border-radius: 2px;
  border: 1px solid turquoise;
  color: pink;
  text-decoration: none;
  padding: 7px 25px;
}
.button--grey {
  display: inline-block;
  border-radius: 2px;
  border: 1px solid pink;
  color:turquoise;
  text-decoration: none;
  padding: 7px 25px;
  margin-left: 15px;
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

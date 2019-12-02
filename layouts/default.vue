<template>
<div>
  <div class="columns is-multiline is-fullheight is-0" id="face" >
    <div class="column is-full">
      <nav class="navbar is-fullwidth is-dark" role="navigation" aria-label="main navigation" style="margin-top:0px">
        <div class="navbar-brand">
          <a class="navbar-item" href="/">
            <p><strong></strong></p>
            <img src="/wp5.png" alt="WP" class="logo">
          </a>
          <a
          role="button"
          class="navbar-burger"
          @click="showNav = !showNav"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample" >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          </a>
          </div>
          <div id="navbarBasicExample" :class="'navbar-menu' + ((showNav == true) ? ' is-active' : '' )">
            <div class="navbar-start">
              <a class="navbar-item" @click="showNav = false"><nuxt-link to="/about"><strong>Profile</strong></nuxt-link>
              </a>
              <a class="navbar-item" @click="showNav = false"><nuxt-link to="/History"><strong>History</strong></nuxt-link>
              </a>
              <a class="navbar-item" @click="showNav = false"><nuxt-link to="/next_Gigs"><strong>GiGS</strong></nuxt-link>
              </a>
                <div class="navbar-item has-dropdown is-hoverable">
                <a class="navbar-link" @click="drop1 = !drop1">
                  Kita
                </a>

                <div class="navbar-dropdown" :style="(drop1 == true)? 'display: block':'display: none'">
                  <a class="navbar-item" @click="showNav = false">
                    <nuxt-link to="/personil/ichi"><strong>iCHi</strong></nuxt-link>
                  </a>
                  <a class="navbar-item" @click="showNav = false">
                    <nuxt-link to="/personil/sam"><strong>Sam</strong></nuxt-link>
                  </a>
                  <a class="navbar-item" @click="showNav = false">
                    <nuxt-link to="/personil/samid"><strong>samID</strong></nuxt-link>
                  </a>
                  <a class="navbar-item" @click="showNav = false">
                    <nuxt-link to="/personil/ananta"><strong>Ananta</strong></nuxt-link>
                  </a>
                  <a class="navbar-item" @click="showNav = false">
                    <nuxt-link to="/personil/gio"><strong>GiO</strong></nuxt-link>
                  </a>
                </div>
              </div>
              <div class="navbar-item has-dropdown is-hoverable">
                <a class="navbar-link" @click="drop2 = !drop2">
                  Lain-lain
                </a>
                <div class="navbar-dropdown" :style="(drop2 == true)? 'display: block':'display: none'">
                  <a class="navbar-item" @click="showNav = false"><nuxt-link to="/media"><strong>Media</strong></nuxt-link>
                  </a>
                  <a class="navbar-item" @click="showNav = false"><nuxt-link to="/SongList"><strong>Song List</strong></nuxt-link>
                  </a>
                  <a class="navbar-item" href="https://www.instagram.com/weabooproject/" @click="showNav = false"> <strong>IG</strong> </a>
                <a class="navbar-item" href="http://youtube.com" @click="showNav = false"> <strong>YT</strong></a>
                </div>
              </div>
            </div>
            <!-- <div class="navbar-end">
              <div class="navbar-item">
                <div class="buttons">
                  <a class="button is-primary" href="/">
                    <strong>HOME</strong>
                  </a>
                </div>
              </div>
            </div> -->
          </div>
      </nav>
    </div>
    <div class="column is-full">
      <nuxt/>
    </div>
    <!-- <div class="column has-background-primary ">
      <footer class="footer">
        <div class="content has-text-centered">
          <p>
            <strong>WEABOO PROJECT</strong>
          </p>
        </div>
        </footer>
  </div> -->
</div>
</div>
</template>

<script>
export default {
  data () {
    return {
      showNav: false,
      drop1: false,
      drop2: false
    }
  }

}
</script>

<style>

</style>
<style scoped>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing:content-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.menu {
  position:fixed;
  top: 10%;
  left:0;
  width: auto;
}
.navbar-dropdown{
  background-color: #3a3a3a;
}

.navbar{
  position:sticky;
  width: 100%;
}
a{
  color: white;
}

.footer{
  bottom: 0;
  align-content: center;
  width: auto;
  justify-content: center;
  text-align:center;
}
.column {
  background: transparent;
  padding:0mm;
}
.logo{
  left: 10%;
}
#navbarBasicExample{
  background-color: #3a3a3a;
}
.navbar-item{
  background: #3a3a3a;
}
</style>

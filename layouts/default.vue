<template>
<div>
  <div class="columns is-multiline is-fullheight is-0" id="face" >
    <div class="column">
      <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a class="navbar-item" href="/">
            <p><strong>W.P</strong></p>
          </a>
          <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          </a>
          </div>
          <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
       <a class="navbar-item" href="/about">
        Profile
      </a>
       <a class="navbar-item" href="/History">
        History
      </a>
        <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          Kita
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            <nuxt-link to="/kita1"><strong>iCHi</strong></nuxt-link>
          </a>
          <a class="navbar-item">
            <nuxt-link to="/kita2"><strong>Sam</strong></nuxt-link>
          </a>
          <a class="navbar-item">
            <nuxt-link to="/kita3"><strong>samID</strong></nuxt-link>
          </a>
          <a class="navbar-item">
            <nuxt-link to="/kita4"><strong>Ananta</strong></nuxt-link>
          </a>
          <a class="navbar-item">
            <nuxt-link to="/kita5"><strong>GiO</strong></nuxt-link>
          </a>
        </div>
      </div>
      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          Lain-lain
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item" href="/media">
            <strong>Media</strong>
          </a>
          <a class="navbar-item" href="/SongList">
            <strong>Song List</strong>
          </a>
          <a class="navbar-item" href="https://www.instagram.com/weabooproject/"> <strong>IG</strong> </a>
        <a class="navbar-item" href="http://youtube.com"> <strong>YT</strong></a>
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
    <!-- <div class="column has-background-primary is-one-fifth is-sidebar-menu is-hidden-mobile"  >
      <aside class="menu ">
        <ul class="menu-list">
          <li><a href="/about">Profile</a></li>
          <li><a href="/History">History</a></li>
           <li>
            <a>kita</a>
            <ul>
              <li><nuxt-link to="/kita1">ichi</nuxt-link></li>
              <li><nuxt-link to="/kita2">sam</nuxt-link></li>
              <li><nuxt-link to="/kita3">samid</nuxt-link></li>
              <li><nuxt-link to="/kita4">ananta</nuxt-link></li>
              <li><nuxt-link to="/kita5">gio</nuxt-link></li>
            </ul>
            </li>
            </ul>
      </aside>
    </div> -->
    <div id="konten" class="column is-full is-gapless" >
      <nuxt/>
    </div>
    <div class="column is-full" style="background: transparent;">
    <footer class="footer">
  <div class="content has-text-centered">
    <p>
      <strong>Weaboo Project</strong> <br> <br><a href="https://jgthms.com"><strong>from Project of Weaboo</strong></a>
    </p>
  </div>
</footer>
  </div>
</div>
</div>
</template>
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

.navbar{
  position:sticky;
  width: 100%;
}
.navbar-end{
align:right;

}
.footer{
  position: static;
  align-content: center;
  width: auto;
  background:transparent;
}
.column {
  background: transparent;
  padding:0mm;
}
.navbar{
  background: transparent;
}
</style>

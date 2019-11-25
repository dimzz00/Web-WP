<template>
<div>
  <div class="columns is-multiline is-fullheight" >
    <div class="column is-full">
      <nav class="navbar is-fullwidth" role="navigation" aria-label="main navigation">
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
       <a class="navbar-item" href="http://youtube.com">
        Kita
      </a>
      <a class="navbar-item" href="http://youtube.com">
        YT
      </a>

      <a class="navbar-item" href="https://www.instagram.com/weabooproject/">
       IG
      </a>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          Lain-lain
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            Media
          </a>
          <a class="navbar-item">
            Contact
          </a>
        </div>
      </div>
    </div>
    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-primary" href="/">
            <strong>HOME</strong>
          </a>
        </div>
      </div>
    </div>
  </div>
      </nav>
    </div>
    <div class="column has-background-primary is-one-fifth is-sidebar-menu is-hidden-mobile"  >
      <aside class="menu ">
        <ul class="menu-list">
          <li><a href="/about">Profile</a></li>
          <li><a href="/History">History</a></li>
           <li>
            <a>kita</a>
            <ul>
              <li><a href="/kita1">iCHi</a></li>
              <li><a href="/kita2">Sam</a></li>
              <li><a href="/kita3">samID</a></li>
              <li><a href="/kita4">Ananta</a></li>
              <li><a href="/kita5">GiO</a></li>
            </ul>
            </li>
            </ul>
      </aside>
    </div>
    <div id="konten" class="column is-four-fifth is-vertical is-fullwidth">
      <nuxt/>
    </div>
    <div class="column has-background-primary is-full">
      <footer class="footer">
        <div class="content has-text-centered">
          <p>
            <strong>WEABOO PROJECT</strong>
          </p>
        </div>
        </footer>
  </div>
</div>
</div>
</template>

<style>
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
  box-sizing: border-box;
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
  position: fixed;
  width: 100%;
}
.footer{
  position: fixed;
  bottom: 0;
  align-content: center;
  width: 100%;
}
.konten {
  background-image: url()
}
</style>

<template>
<div>
  <div class="columns is-multiline is-fullheight" >
    <div class="column is-full">
      <nav class="navbar is-fullwidth" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a class="navbar-item" href="https://bulma.io">
            <img src="" alt="TEST">
          </a>
          <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          </a>
          </div>
          <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item">
        -
      </a>

      <a class="navbar-item">
        -
      </a>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          -
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            ---
          </a>
          <a class="navbar-item">
            ---
          </a>
          <a class="navbar-item">
            Contact
          </a>
          <hr class="navbar-divider">
          <a class="navbar-item">
            ---
          </a>
        </div>
      </div>
    </div>
    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-primary">
            <strong>----</strong>
          </a>
          <a class="button is-light">
            ------
          </a>
        </div>
      </div>
    </div>
  </div>
      </nav>
    </div>
    <div class="column has-background-info is-one-quarter is-sidebar-menu is-hidden-mobile"  >
      <aside class="menu ">
        <p class="menu-label">
          ???????????????????
        </p>
        <ul class="menu-list">
          <li><a>------------------</a></li>
          <li><a>------------------</a></li>
        </ul>
        <p class="menu-label">
          ???????????????????
        </p>
        <ul class="menu-list">
          <li><a>------------------</a></li>
          <li>
            <a>------------------</a>
            <ul>
              <li><a>------------------</a></li>
              <li><a>------------------</a></li>
              <li><a>------------------</a></li>
            </ul>
          </li>
          <li><a>------------------</a></li>
          <li><a>------------------</a></li>
          <li><a>------------------</a></li>
        </ul>
        <p class="menu-label">
          ???????????????
        </p>
        <ul class="menu-list">
          <li><a>------------------</a></li>
          <li><a>------------------</a></li>
          <li><a>------------------</a></li>
        </ul>
      </aside>
    </div>
    <div id="konten" class="column is-three-quarters is-vertical is-fullwidth">
      <nuxt/>
    </div>
    <div class="column is-full">
      <footer class="footer">
        <div class="content has-text-centered">
          <p>
            Kosongin dulu ae gan XD
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

</style>

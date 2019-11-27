<template>
<div class="container3">
  <nuxt/>
  <!-- <div class="columns">
    <div class="column is-full" >
      <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a class="navbar-item" href="">
            <img src="" alt="Weboo Project" width="112" height="28">
          </a>
          <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          </a>
          </div>
      </nav>
    </div>
    <div class="column is-four-fifths">
       <nuxt/>
    </div>
  </div>
  <div class="content">
  </div>
  <div class="columns">
  <div class="column is-full">
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          Kosongin dulu ae gan XD
        </p>
      </div>
      </footer>
  </div>
  </div> -->
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
  border: 1px solid turquoise;
  color: white;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: white;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid pink;
  color: white;
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
  width: 100%;
}

.navbar{
  position: fixed;
}
.footer:scope{
  position: fixed;
  bottom: 0;
  align-content: center;
  width: 100%;
}
.container3 {
  background-image: url('/punggung.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  color: white;
}
</style>

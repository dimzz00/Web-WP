<template>
  <div class="container2">
    <div class="container4">
    <div class="tile is-ancestor">
  <div class="tile is-vertical is-8">
    <div class="tile">
      <div class="tile is-parent is-vertical">
        <article class="tile is-child notification is-primary">
          <p class="title">VIRAL! Wibu jadi tulang punggung negara</p>
          <p class="subtitle">para wibu sudah menjadi berkembang sejak wibu project hadir di jagat perwibuan</p>
          <img src="sashimi.jpg" style="opacity:1">
        </article>
        <article class="tile is-child notification is-warning">
          <p class="title">Wibu project menyerang</p>
          <p class="subtitle">dikabarkan perwibuan indonesia gempar denagn sebuah fenomena</p>
        </article>
      </div>
      <div class="tile is-parent">
        <article class="tile is-child notification is-info">
          <p class="title">INI DIA JADWAL MANGGUNG BAND YANG VIRAL</p>
          <p class="subtitle">tapi boong</p>
          <figure class="poto">
            <img src="Weaboo.jpg">
          </figure>
        </article>
      </div>
    </div>
    <div class="tile is-parent">
      <article class="tile is-child notification is-danger">
        <p class="title">WIBU PROJECT jadi OPENING OLIMPIADE JAKARTA-BOJONGSOANG 2032</p>
        <p class="subtitle">setelah ditetapkannya olimpiade di indonesia, panitia olimpiade sudah mengeluarkan daftar artis untuk menjadi performer yang akan tampil di opening ceremony</p>
        <div class="content">
          <!-- Content -->
        </div>
      </article>
    </div>
  </div>
  <div class="tile is-parent">
    <article class="tile is-child notification is-success">
      <div class="content">
        <p class="title">Ternyata SEMUA judul berita yang kalian lihat dihalam ini adalah PALSU!!!</p>
        <p class="subtitle">ya iyalahh ngayal dikit boleh dong</p>
        <img src="kontet.jpeg">
        <img src="kontet.jpeg">
        <img src="kontet.jpeg">
        <div class="content">
          <!-- Content -->
        </div>
      </div>
    </article>
  </div>
</div>
    <!-- <div> -->
      <!-- <h1 class="title_NG">
        Coming soon
      </h1>
      <h2 class="subtitle_NG">
        "Next Update"
      </h2> -->
      <!-- <div class="links">
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
      </div> -->
    <!-- </div> -->
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  components: {
  }
}
</script>

<style>
.container4 {
  margin: 3% ;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  align-items: center;
    background-image: url('/back4.png');
    background-size: cover;
    background-attachment: fixed;
}

.title_NG {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: white;
  letter-spacing: 1px;
  position: fixed;
  left: 40%;
  top:30%;
}

.subtitle_NG {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
  position: fixed;
  left: 40%;
}

.links {
  padding-top: 15px;
  position: fixed;
  top:40%;
  left:60%;
}
.tile is-parent:hover{
  transform: scale(1.2);
}
@media (max-width: 769px){
  .container4{
    padding-right: 5%;
    padding-left: 5%;
  }
}
</style>

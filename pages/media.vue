<template>
  <div class="container2">
    <div class="columns1 is-multiline">
      <div class="column3 is-full">
        <div class="tabs">
          <ul>
            <li :class="'tablink ' + ((activeTabs == 'pictures') ? 'is-active' : '')" @click="activeTabs = 'pictures'">
              <a>Gambar</a>
            </li>
            <li :class="'tablink ' + ((activeTabs == 'Musics') ? 'is-active' : '')" @click="activeTabs = 'Musics'">
              <a>Lagu</a>
            </li>
            <li :class="'tablink ' + ((activeTabs == 'video') ? 'is-active' : '')" @click="activeTabs = 'video'">
              <a>YuSup PlayList</a>
            </li>
          </ul>
        </div>
        <div class="content">
          <div class="column">
            <div :class="'modal' + ((activeModal == activeClick) ? ' is-active is-clipped' : '')">
              <div class="modal-background" />
              <div class="modal-content">
                <p class="image is-16by9">
                  <img :src="personil[activePict]" alt="">
                </p>
                <h4>{{ personil[activePict] }}</h4>
              </div>
              <button @click="activeClick = false" class="modal-close is-large" aria-label="close" />
            </div>
            <div v-if="activeTabs == 'pictures'">
              <h3 class="is-three">
                Gambar's
              </h3>
              <div class="columns is-multiline">
                <div class="column is-one-third">
                  <figure class="is-2by1">
                    <img @click="activeClick = true, activePict = 'ichi'" src="ichi.png" alt="">
                  </figure>
                </div>
                <div class="column is-one-third">
                  <figure class="is-2by1">
                    <img @click="activeClick = true, activePict = 'ananta'" src="ananta.png" alt="">
                  </figure>
                </div>
                <div class="column is-one-third">
                  <figure class="is-2by1">
                    <img @click="activeClick = true, activePict = 'gio'" src="Gio.jpg" alt="">
                  </figure>
                </div>
                <div class="column is-one-third">
                  <figure class="is-2by1">
                    <img @click="activeClick = true, activePict = 'sam'" src="sam.png" alt="">
                  </figure>
                </div>
                <div class="column is-one-third">
                  <figure class="is-2by1">
                    <img @click="activeClick = true, activePict = 'samid'" src="samid.png" alt="">
                  </figure>
                </div>
              </div>
            </div>
            <div v-if="activeTabs == 'video'" class="content">
              <h3 class="is-three">
                Yusup Playlist WP
              </h3>
              <iframe class="yt" width="720" height="480" src="https://www.youtube.com/embed/videoseries?list=PLfH8pFcI2uJtCuZ9eSa1edKvJoOGruuJ6" />
            </div>
            <div v-if="activeTabs == 'Musics'">
              <h3 class="is-three">
                Musics
              </h3>
              <p>
                sjfmkfndksnfjsndfkmiekmfkdmfosnmdknfe.
                kfkdsmfksdmfklmeknfmkdnsfmndfjenkfnmdnsjenf.
                kdsfmdksnfjenmfmdsfnnfnejfnmmslnfalnlfknklnfonwe.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      activePict: '',
      saus: '',
      activeModal: true,
      activeClick: false,
      activeTabs: 'pictures',
      personil: {
        sam: '/ichi.png',
        ichi: '/ichi.png',
        ananta: '/ichi.png',
        gio: '/ichi.png',
        samid: '/ichi.png'
      }
    }
  }
}
</script>

<style scoped>

.container2 {
  margin: center;
  min-height: 100vh;
  display: flex;
  justify-content:center;
  align-items: center;
  text-align:center;
  background-image: url('/back5.png');
  background-size:cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: White;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
}
div figure .yt{
  align-items: center;
  text-align: center;
}
.content{
  align-items: center;
  text-align: center;
}

.links {
  padding-top: 15px;
}
.tabs{
  background : rgb(135, 206, 235, 0.3);
  /* background-size:contain;
  position: relative;
  top : 50%; */
}

div .tabs a {
  font-weight: bold;
  color: white;
}
div .columns1 {
  background: rgb(135, 206, 235, 0.3);
  filter:blur(5);
  width: 95%;
  position: static;
}

div .columns1 h3 {
  font-weight: bold;
  color: #000000;
}

/* .TContent{
  display : none;
} */

/* #Pictures{
  display : block;
} */

@keyframes slidy {
0% { left: 0%; }
20% { left: 0%; }
25% { left: -100%; }
45% { left: -100%; }
50% { left: -200%; }
70% { left: -200%; }
75% { left: -300%; }
95% { left: -300%; }
100% { left: -400%; }
}

div #slider { overflow: hidden; }

div #slider figure img { width: 20%; float: left; }

div #slider figure {
  position: relative;
  width: 500%;
  margin: 0;
  left: 0;
  text-align: left;
  font-size: 0;
  animation: 30s slidy infinite;
}
@media (max-width: 769px){
.yt{
  width: 270px;
  height: 180px;
  justify-content: center;
  align-items: center;
  text-align: center;
}
}
@media (min-width: 769px) and (max-width: 1023px) {
  .yt{
  width: 540px;
  height: 360px;
  justify-content: center;
  align-items: center;
  text-align: center;
  }
}
</style>

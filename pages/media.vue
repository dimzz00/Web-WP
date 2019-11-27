<template>
<section class="hero is-info">
  <div class="hero-body">
    <div class="container2">
      <div class="columns1 is-multiline">
        <div class="column3 is-full">
          <div class="tabs">
            <ul>
              <li :class="'tablink ' + ((activeTabs == 'pictures') ? 'is-active' : '')" @click="activeTabs = 'pictures'"><a>Gambar</a></li>
              <li :class="'tablink ' + ((activeTabs == 'Musics') ? 'is-active' : '')" @click="activeTabs = 'Musics'"><a>Lagu</a></li>
              <li :class="'tablink ' + ((activeTabs == 'video') ? 'is-active' : '')" @click="activeTabs = 'video'"><a>YuSup PlayList</a></li>
            </ul>
          </div>
          <div class="content">
            <div class="column">
              <div v-if="activeTabs == 'pictures'" >
                <h3 class="is-three">Gambar's</h3>
                  <div id="slider">
                    <figure>
                      <img src="ichi.png" alt="">
                      <img src="ananta.png" alt="">
                      <img src="Gio.jpg" alt="">
                      <img src="sam.png" alt="">
                      <img src="samid.png" alt="">
                    </figure>
                  </div>
                  <!-- <div class="columns is-0 is-multiline is-mobile">
                    <div class="column is-one-quarter-desktop is-half-tablet">
                      <div class="tabPict" @click="modalPict == 'ichi'">
                        <figure class="image is-2by1">
                          <img src="ichi.png">
                        </figure>
                      </div>
                    </div>
                    <div class="column is-one-quarter-desktop is-half-tablet">
                      <figure class='image is-2by1' @click="modalPict == 'ananta'">
                        <img src="ananta.png">
                      </figure>
                    </div>
                    <div class="column is-one-quarter-desktop is-half-tablet">
                      <figure class="image is-2by1" @click="modalPict == 'gio'">
                        <img src="Gio.jpg">
                      </figure>
                    </div>
                    <div class="column is-one-quarter-desktop is-half-tablet">
                      <figure class="image is-2by1" @click="modalPict == 'sam'">
                        <img src="sam.png">
                      </figure>
                    </div>
                    <div class="column is-one-quarter-desktop is-half-tablet">
                      <figure class="image is-2by1" @click="modalPict == 'samid'">
                        <img src="samid.png">
                      </figure>
                    </div>
                    <div>
                    <my-modal v-if="modalPict == 'ichi'">
                      <figure class="image">
                        <img src="ichi.png">
                      </figure>
                    </my-modal>
                    </div>
                  </div> -->
              </div>
              <div v-if="activeTabs == 'video'" >
                <h3 class="is-three">Yusup Playlist WP</h3>
                <portal to="destination">
                  <p>This slot content will be rendered wherever the with name 'destination' is  located.</p>
                </portal>
                <portal-target name="destination">
                  This component can be located anywhere in your App.
                  The slot content of the above portal component will be rendered here.
                </portal-target>
                <figure class="video">
                  <iframe
                  width="720"
                  height="480"
                  src="https://www.youtube.com/embed/videoseries?list=PLfH8pFcI2uJtCuZ9eSa1edKvJoOGruuJ6"
                  frameborder="0"
                  allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen>
                  </iframe>
                </figure>
              </div>
              <div v-if="activeTabs == 'Musics'" >
                <h3 class="is-three">Musics</h3>
                <p>sjfmkfndksnfjsndfkmiekmfkdmfosnmdknfe.
                  kfkdsmfksdmfklmeknfmkdnsfmndfjenkfnmdnsjenf.
                  kdsfmdksnfjenmfmdsfnnfnejfnmmslnfalnlfknklnfonwe.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
    </section>
</template>

<script>
export default {

  data () {
    return {
      modalPict: '',
      activeTabs: 'pictures'
    }
  },

  methods: {
    openTab (event, tabId) {
      // console.log(event.target)
    //   const tabcontent = document.getElementsByClassName('TContent')
    //   for (let i = 0; i < tabcontent.length; i++) {
    //     tabcontent[i].style.display = 'none'
    //   }
    // const tablink = document.getElementsByClassName('tablink')
    // for (let i = 0; i < tablink.length; i++) {
    //   tablink[i].className = tablink[i].className.replace(' is-active', '')
    // }
    // document.getElementById(tabId).style.display = 'block'
    // event.currentTarget.className += 'is-active'
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
</style>

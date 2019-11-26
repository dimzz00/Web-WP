<template>
<section class="hero is-info">
  <div class="hero-body">
    <div class="container">
      <div class="columns1 is-multiline">
        <div class="column3 is-full">
          <div class="tabs">
            <ul>
              <li :class="'tablink ' + ((activeTabs == 'pictures') ? 'is-active' : '')" @click="activeTabs = 'pictures'"><a>Pictures</a></li>
              <li :class="'tablink ' + ((activeTabs == 'Musics') ? 'is-active' : '')" @click="activeTabs = 'Musics'"><a>Musics</a></li>
              <li :class="'tablink ' + ((activeTabs == 'video') ? 'is-active' : '')" @click="activeTabs = 'video'"><a>Video</a></li>
            </ul>
          </div>
          <div class="content">
            <div class="column">
              <div v-if="activeTabs == 'pictures'" >
                <h3 class="is-three">Pictures</h3>
                  <div class="columns is-0 is-multiline is-mobile">
                    <div class="column is-one-quarter-desktop is-half-tablet">
                          <figure class="image is-2by1">
                            <img src="https://unsplash.it/300/200/?random&pic=3">
                          </figure>
                    </div>
                    <div class="column is-one-quarter-desktop is-half-tablet">
                      <figure class="image is-2by1">
                        <img src="ananta.png">
                        <img src="ananta.png">
                      </figure>
                    </div>
                  </div>
              </div>
              <div v-if="activeTabs == 'video'" >
                <h3 class="is-three">Videos</h3>
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
.container {
  margin: center;
  min-height: 100vh;
  display: flex;
  justify-content:center;
  align-items: center;
  text-align:center;
  background-image: url(back2.png);
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
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
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
  color: #000000;
}
div .columns1 {
  background: rgb(135, 206, 235, 0.3);
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
</style>

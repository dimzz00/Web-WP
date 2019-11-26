<template>
<div class="container">
  <div class="columns1 is-multiline is-fullheight ">
    <div class="column3 is-full">
      <div class="tabs">
        <ul>
          <li :class="'tablink ' + (activeTabs == 'pictures') ? 'is-active' : ''" @click="activeTabs = 'pictures'"><a>Pictures</a></li>
          <li :class="'tablink ' + (activeTabs == 'Musics') ? 'is-active' : ''" @click="activeTabs = 'Musics'"><a>Musics</a></li>
          <li :class="'tablink ' + (activeTabs == 'video') ? 'is-active' : ''" @click="activeTabs = 'video'"><a>Video</a></li>
        </ul>
      </div>
      <div class="content">
        <div class="column3 is-full">
          <div v-if="activeTabs == 'pictures'" >
            <h3 class="is-three">Pictures</h3>
            <p>sjfmkfndksnfjsndfkmiekmfkdmfosnmdknfe.
              kfkdsmfksdmfklmeknfmkdnsfmndfjenkfnmdnsjenf.
              kdsfmdksnfjenmfmdsfnnfnejfnmmslnfalnlfknklnfonwe.
            </p>
          </div>
          <div v-if="activeTabs == 'video'" >
            <h3 class="is-three">Videos</h3>
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
  margin: 0 auto;
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
  background-color: lightgray;
  /* background-size:contain;
  position: relative;
  top : 50%; */
}
.columns1{
  /* opacity: 50%; */
}

.column3{
  background-color: lightgray;
}

/* .TContent{
  display : none;
} */

/* #Pictures{
  display : block;
} */
</style>

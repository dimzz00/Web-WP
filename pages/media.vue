<template>
<div class="container">
  <div class="columns1 is-multiline is-fullheight ">
    <div class="column3 is-full">
      <div class="bd-notification is-Light">
      <div class="tabs">
        <ul>
          <li  onclick=()><a>Pictures</a></li>
          <li><a>Music</a></li>
          <li class="is-active"><a>Videos</a></li>
          <li><a>Documents</a></li>
        </ul>
      </div>
    </div>
    <div class="column3 is-full">
      <div id="pictures" class="TContent">
        <p class="is-three">Pictures</p>
        <p>sjfmkfndksnfjsndfkmiekmfkdmfosnmdknfe.
          kfkdsmfksdmfklmeknfmkdnsfmndfjenkfnmdnsjenf.
          kdsfmdksnfjenmfmdsfnnfnejfnmmslnfalnlfknklnfonwe.
        </p>
      </div>
      <div id="Video" class="TContent">
        <p class="is-three">Videos</p>
        <p>
          <iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLfH8pFcI2uJtCuZ9eSa1edKvJoOGruuJ6" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture; fullscreen" ></iframe>
        </p>
      </div>
      <div id="Music" class="TContent">
        <p class="is-three">Musics</p>
        <p>sjfmkfndksnfjsndfkmiekmfkdmfosnmdknfe.
          kfkdsmfksdmfklmeknfmkdnsfmndfjenkfnmdnsjenf.
          kdsfmdksnfjenmfmdsfnnfnejfnmmslnfalnlfknklnfonwe.
        </p>
      </div>
    </div>
    </div>
  </div>
</div>
</template>

<script>
export default {

}
</script>

<style>

</style>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  components: {
    // Logo
  }
}
</script>

<style>
.container {
  background-image: url("punggung.jpg");
  background-position: 97% 100%;
  background-repeat:  no-repeat;
  background-attachment: fixed;
  background-size: contain;
  background-color: rgb(243, 101, 6);
  margin: 0;
  padding: 0%;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  width: auto;
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

</style>

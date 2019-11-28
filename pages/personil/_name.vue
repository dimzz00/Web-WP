<template>
  <!-- <div class="container2" :style="{ 'background-image': 'url(' + item.background + ')' }">
    <div v-for="(item, index) in personil" :key="index">
      {{ item.nama }}
    </div>
    <div v-if="item" class="card">
      <p>{{ item.nama }} umur {{ item.umur }}</p>
    </div>
    <div v-else>Tidak ada personil dengan nama: {{ $route.params.name }}</div>
  </div> -->
  <div class="container2" :style="{ 'background-image': 'url(' + item.background + ')' }">
     <div class="content" v-if="item">
        <p class="title">{{ item.nama }}</p>
        <p class="subtitle">{{ item.data }}</p>
        <iframe class="yt" width="540" height="360" :src="item.yusup"></iframe>
    </div>
    </div>
</template>

<script>
export default {
  data () {
    return {
      personil: {
        sam: {
          nama: 'Sam',
          data: 'Setengah Wibu. Setengah maS-maS biasa',
          background: '"/sam.png"',
          yusup: ''
        },
        ichi: {
          nama: 'iCHi',
          data: 'Jadi Wibu Setengah-Setengah',
          background: '/ichi.png',
          yusup: ''
        },
        ananta: {
          nama: 'Ananta',
          data: 'Wibu Anteng',
          background: '/ananta.png',
          yusup: ''
        },
        gio: {
          nama: 'GiO',
          data: 'Setengah Wibu setengah Normal',
          background: '/gio.jpg',
          yusup: 'https://www.youtube.com/embed/videoseries?list=PLw-LNUHX2AEj9VutIAJb2g_PTDGg7ddTI'
        },
        samid: {
          nama: 'SamID',
          data: 'Setengah Wibu, WIBU setengah-setengah',
          background: '/samid.png',
          yusup: 'https://www.youtube.com/embed/videoseries?list=PLwsQ6fwvIIxO35gnAn7ImIbtjt32g0-Cg'
        }
      }
    }
  },
  computed: {
    item () {
      return this.personil[this.$route.params.name] // personil['sam']
    }
  }
}
</script>

<style scoped>

.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-image: url('/ichi.png')
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
  'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-weight: 300;
  font-size: 100px;
  color:white;
  letter-spacing: 1px;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: white;
  word-spacing: 5px;
  padding-bottom: 15px;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.links {
  padding-top: 15px;
}
.content{
    color: white;
}
</style>

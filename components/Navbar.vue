<template>
  <nav class="navbar is-fullwidth is-dark" role="navigation" aria-label="main navigation" style="margin-top:0px">
    <div class="navbar-brand">
      <nuxt-link class="navbar-item" to="/">
        <p><strong /></p>
        <img src="/wp5.png" alt="WP" class="logo">
      </nuxt-link>
      <a
        @click="showNav = !showNav"
        role="button"
        class="navbar-burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
      >
        <span aria-hidden="true" />
        <span aria-hidden="true" />
        <span aria-hidden="true" />
      </a>
    </div>
    <div id="navbarBasicExample" :class="'navbar-menu' + ((showNav == true) ? ' is-active' : '' )">
      <div class="navbar-start">
        <nuxt-link id="link" @click="showNav = false" to="/about" class="navbar-item">
          <strong>Profile</strong>
        </nuxt-link>
        <nuxt-link id="link" @click="showNav = false" to="/history" class="navbar-item">
          <strong>History</strong>
        </nuxt-link>
        <nuxt-link id="link" @click="showNav = false" to="/next_gigs" class="navbar-item">
          <strong>News</strong>
        </nuxt-link>
        <div @click="drop1 = !drop1" class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link" style="color: pink">
            Kita
          </a>

          <div :style="(drop1 == true)? 'display: block':'display: none'" class="navbar-dropdown">
            <nuxt-link
              id="link"
              @click="showNav = false , drop1 = false"
              v-for="item in personil"
              v-bind:key="item"
              :to="'/personil/' + item.name.toLowerCase()"
              class="navbar-item"
            >
              <strong>{{ item.name }}</strong>
            </nuxt-link>
          </div>
        </div>
        <div class="navbar-item has-dropdown is-hoverable">
          <a @click="drop2 = !drop2" class="navbar-link" style="color: pink">
            Lain-lain
          </a>
          <div :style="(drop2 == true)? 'display: block':'display: none'" class="navbar-dropdown">
            <nuxt-link id="link" @click="showNav = false , drop2 = false" to="/media" class="navbar-item">
              <strong>Media</strong>
            </nuxt-link>
            <nuxt-link id="link" @click="showNav = false , drop2 = false" to="/SongList" class="navbar-item">
              <strong>Song List</strong>
            </nuxt-link>
            <a
              id="link"
              @click="showNav = false , drop2 = false"
              class="navbar-item"
              href="https://www.instagram.com/weabooproject/"
            > <strong>IG</strong> </a>
            <a
              id="link"
              @click="showNav = false , drop2 = false"
              class="navbar-item"
              href="http://youtube.com"
            > <strong>YT</strong></a>
          </div>
        </div>
      </div>
      <!-- <div class="navbar-end">
              <div class="navbar-item">
                <div class="buttons">
                  <a class="button is-primary" href="/">
                    <strong>HOME</strong>
                  </a>
                </div>
              </div>
            </div> -->
    </div>
  </nav>
</template>

<script>
export default {
  data () {
    return {
      showNav: false,
      drop1: false,
      drop2: false,
      personil: {
        sam: {
          name: 'Sam'
        },
        samid: {
          name: 'SamID'
        },
        ichi: {
          name: 'iCHi'
        },
        ananta: {
          name: 'Ananta'
        },
        gio: {
          name: 'GiO'
        }
      }
    }
  }

}
</script>

<style>
.navbar-dropdown {
  background-color: #3a3a3a;
}

.navbar {
  position:sticky;
  width: 100%;
}
#link {
  color: pink;
}
</style>

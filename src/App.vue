<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'ComicsApp',
  components: { AppHeader, AppMain, AppFooter }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Generics */
body {
  height: 100vh;
  background-color: #fff;
  font-family: 'Encode Sans Condensed', sans-serif;
}

img {
  max-width: 100%;
  height: auto;
}

a {
  color: black;
  text-decoration: none;
}

/* Utils */
.container {
  max-width: 1400px;
  margin: 0 auto;
}
</style>

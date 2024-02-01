<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'

export default {
  name: 'ComicsApp',
  components: { AppHeader, AppMain }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <footer></footer>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Generics */
img {
  max-width: 100%;
  height: auto;
}

a {
  color: black;
  text-decoration: none;
}

body {
  font-family: 'Encode Sans Condensed', sans-serif;
}

/* Utils */
.container {
  max-width: 1400px;
  margin: 0 auto;
}
</style>

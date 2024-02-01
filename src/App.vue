<script>
import AppHeader from './components/AppHeader.vue'

export default {
  name: 'ComicsApp',
  components: {
    AppHeader
  }
}
</script>

<template>
  <AppHeader />
  <main></main>
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
</style>

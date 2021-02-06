<template>
  <Header />
</template>

<script>
import Header from './components/header/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
html {
  font-family: arial,sans-serif;
    a, a:hover, a:focus, a:active {
    text-decoration: none;
    color: inherit;
  }
}
body {
  margin: 0;
}
</style>

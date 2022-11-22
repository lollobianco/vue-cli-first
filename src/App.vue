<template>
  <div id="app">

    <HeroItem/>
    <AppTitle/>

  </div>
</template>

<script>

import AppTitle from './components/AppTitle.vue'
import HeroItem from './components/HeroItem.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    HeroItem,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0px;
  padding: 0;
}
</style>

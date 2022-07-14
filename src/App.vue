<template>
  <div id="app">
    <HeroNewName/>
  </div>
</template>

<script>

import HeroNewName from './components/HeroNewName.vue'
export default {
  name: 'App',
  components: {
    HeroNewName
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
  margin-top: 60px;
}
</style>

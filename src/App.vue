<template>
<div id="app">
  <TitleProject />
  <HeroImg />
</div>
</template>

<script>
import TitleProject from './components/TitleProject.vue'
import HeroImg from './components/HeroImg.vue'

export default {
  name: 'App',
  components: {
    TitleProject, 
    HeroImg
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

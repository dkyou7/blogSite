<template>
  <div id="app">
    <site-title/>
    <Article/>
    <vertical-menu/>
    <horizental-menu/>
  </div>
</template>

<script>
import SiteTitle from './components/SiteTitle.vue'
import Article from './components/Article.vue'
import VerticalMenu from './components/VerticalMenu.vue'
import HorizentalMenu from './components/HorizentalMenu.vue'

export default {
  name: 'app',
  components: {
    SiteTitle,
    Article,
    VerticalMenu,
    HorizentalMenu
  }
}
</script>

<style>
.app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

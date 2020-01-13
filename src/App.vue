<template>
  <div id="app">
    <site-title/>
    <horizental-menu/>
    <div class="boxA">
      <Article class="article"/>
      <vertical-menu class="vertical_menu"/>
    </div>
    <Copyright/>
  </div>
</template>

<script>
import SiteTitle from './components/SiteTitle.vue'
import Article from './components/Article.vue'
import VerticalMenu from './components/VerticalMenu.vue'
import HorizentalMenu from './components/HorizentalMenu.vue'
import Copyright from './components/Copyright.vue'

export default {
  name: 'app',
  components: {
    SiteTitle,
    Article,
    VerticalMenu,
    HorizentalMenu,
    Copyright
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
.boxA::after{
  content: '';
  display: block;
  clear: both;
}
.article{
  float: left;
  width: 70%;
}
.vertical_menu{
  width: 30%;
  float: left;
}
</style>

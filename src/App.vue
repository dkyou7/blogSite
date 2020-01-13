<template>
  <div id="app">
    <site-title class="siteTitle"/>
    <horizental-menu class="horizental_menu"/>
    <div class="boxA">
      <Article class="article"/>
      <vertical-menu class="vertical_menu"/>
    </div>
    <Copyright class="copyright"/>
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

@media(min-width: 768px){

  .boxA::after{
    content: '';
    display: block;
    clear: both;
  }
  .vertical_menu{
    width: 30%;
    float: left;
    padding: 30px 0 40px 0;
  }
  .article{
    float: left;
    width: 70%;
    padding: 40px 0 30px 0;
    padding-right: 50px;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
  }
}

.horizental_menu{
  background-color: #7cbac1;
}
.copyright{
  border-top: solid 1px #dddddd;
  padding: 15px 0 15px 0;
}
.siteTitle{
  padding: 8px 0 8px 0;
}

@media(min-width:900px){
    #app{
      width: 900px;
      margin-left: auto;
      margin-right: auto;
    }
}
</style>

<template>
  <div class="menu">
      <ul>
          <li><a href="#">메인</a></li>
          <li><a href="#">잡화</a></li>
          <li><a href="#">도구</a></li>
          <li><a href="#">외출</a></li>
          <li><a href="#">음식</a></li>
          <li><a href="#">문의</a></li>
      </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .menu ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .menu li a{
        display: block;
        padding: 5px;
        color: #000000;
        font-size: 15px;
        text-decoration: none;
    }
    .menu li a:hover{
        background-color: #e3e3e3;
    }
    .menu ul::after{
        content: '';
        display: block;
        clear: both;
    }
    .menu ul li{
        float: left;
        width: auto;
    }
</style>
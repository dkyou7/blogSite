<template>
  <div class="site">
      <h1><a href="#">TimeSwitch</a></h1>
      <p>매일 생활과 관련된 것을 올리는 블로그</p>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .site h1 a{
        color: #000000;
        text-decoration: none;
    }
    .site h1{
        margin: 0;
        font-size: 30px;
    }
    .site p{
        margin:0;
        font-size: 12px;
    }
    @media(max-width: 599px){
        .site h1{
            font-size: 20px;
        }
    }
</style>
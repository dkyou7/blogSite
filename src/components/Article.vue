<template>
  <article class="story">
      <h1>토마토를 맛있게 먹는 방법</h1>

      <img src="../assets/img/03/tomato.jpg" alt="">

      <p>
          수확한 토마토를 바로 먹고 싶어서  서울 외곽에 있는 토마토 농가에 직접 다녀왔습니다.
          이번에 온 농가의 토마토는 신선하고 저렴하군요.
      </p>
      <p>
          수확한 토마토를 바로 먹고 싶어서  서울 외곽에 있는 토마토 농가에 직접 다녀왔습니다.
          이번에 온 농가의 토마토는 신선하고 저렴하군요.!
      </p>

  </article>
</template>

<script>
export default {

}
</script>

<style scoped>
    .story h1{
        margin-top: 0;
        margin-bottom: 20px;
        font-size: 36px;
    }
    .story p{
        margin-top: 0;
        margin-bottom: 20px;
    }
    .story img{
        width: 100%;
        height: auto;
    }
    @media(max-width: 599px){
        .story h1{
            font-size: 26px;
        }
    }
</style>
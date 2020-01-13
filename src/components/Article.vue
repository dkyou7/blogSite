<template>
  <article class="story">
      <div class="story-cat">
          <ul>
              <li><a href="#">음식</a></li>
              <li><a href="#">외출</a></li>
          </ul>
      </div>
      <h1>토마토를 맛있게 먹는 방법</h1>
      <div class="storyInfo">
          <i class="fa fa-clock-o"></i><time datetime="2020-01-13">2020년 1월 13일</time>
      </div>

      <img src="../assets/img/03/tomato.jpg" alt="">

    <h2>신선한 토마토 구별 방법</h2>
    <p>
        수확한 토마토를 바로 먹고 싶어서  서울 외곽에 있는 토마토 농가에 직접 다녀왔습니다.
        이번에 온 농가의 토마토는 신선하고 저렴하군요.
    </p>

    <h2>신선한 토마토 구별 방법</h2>
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
    .storyInfo{
        margin-top: -10px;
        margin-bottom: 20px;
    }
    .storyInfo i{
        margin-right: 5px;
        color: #aaaaaa;
        font-size: 20px;
    }
    @media(max-width: 599px){
        .story h1{
            font-size: 26px;
        }
    }


    .story-cat{
        margin-bottom: 25px;
    }
    .story-cat ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .story-cat ul li a{
        display: block;
        margin-right: 5px;
        padding: 3px 5px;
        border-radius: 3px;
        background-color: #75dbe7;
        color: #ffffff;
        font-size: 12px;
        text-decoration: none;
    }
    .story-cat ul li a:hover{
        background-color: #94ecf6;
    }
    .story-cat ul::after{
        content: '';
        display: block;
        clear: both;
    }
    .story-cat li{
        float: left;
        width: auto;
    }

    .story h2{
        margin-top: 40px;
        padding-left: 10px;
        border-left: solid 10px #7cbac1;
        font-weight: normal;
    }
</style>
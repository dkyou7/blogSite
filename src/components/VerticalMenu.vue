<template>
<div>
  <nav class="sidemenu">
      <h1>특집 기사</h1>
      <ul>
          <li><a href="#">알기 쉬운 지도 읽기 방법</a></li>
          <li><a href="#">처음부터 시작하는 토마토 기르기</a></li>
          <li><a href="#">svn 설정 방법</a></li>
          <li><a href="#">로지택 연동하는 방법</a></li>
      </ul>
  </nav>
  <nav class="recommend">
      <h1>추천 기사</h1>
      <ul>
          <li><a href="#">처음부터 시작하는 꽃꽃이</a></li>
          <li><a href="#">오래된 스마트폰을 충전했더니..</a></li>
      </ul>
  </nav>
  <nav class="popular">
      <h1>인기 기사</h1>
      <ul>
          <li><a href="#">꽃을 좋아하는 사람들을 위한 포인트</a></li>
          <li><a href="#">웹앱 어플리케이션 개발의 기초</a></li>
          <li><a href="#">세계 각지의 쇼핑백</a></li>
      </ul>
  </nav>
</div>

</template>

<script>
export default {

}
</script>

<style scoped>
    .sidemenu ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .sidemenu li a{
        display: block;
        padding: 5px;
        color: #000000;
        font-size: 15px;
        text-decoration: none;
    }
    .sidemenu li a:hover{
        background-color: #e3e3e3;
    }
    .sidemenu h1{
        border-bottom: dotted 2px #666666;
        color: #666666;
    }
    .sidemenu{
        margin-bottom: 30px;
    }

    .recommend ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .recommend li a{
        display: block;
        padding: 5px;
        color: #000000;
        font-size: 15px;
        text-decoration: none;
    }
    .recommend li a:hover{
        background-color: #e3e3e3;
    }
    .recommend h1{
        border-bottom: dotted 2px #666666;
        color: #666666;
    }
    .recommend  {
        margin-bottom: 30px;
    }

    .popular ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .popular li a{
        display: block;
        padding: 5px;
        color: #000000;
        font-size: 15px;
        text-decoration: none;
    }
    .popular li a:hover{
        background-color: #e3e3e3;
    }
    .popular h1{
        border-bottom: dotted 2px #666666;
        color: #666666;
    }
    .popular{
        margin-bottom: 30px;
    }
</style>
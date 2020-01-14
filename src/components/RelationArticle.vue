<template>
  <aside class="relation">
      <h1>관련 기사</h1>
      <ul>
          <li>
                <a href="#">
                    <img src="../assets/img/03/red-150x150.jpg" alt="">
                    <div class="text">
                        토마토 재배 8화 - 토마토들이 붉은색으로 물들기 시작합니다.
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/img/03/potato-150x150.jpg" alt="">
                    <div class="text">
                        맛있는 감자요리
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/img/03/eggplant-150x150.jpg" alt="">
                    <div class="text">
                        가지를 수확했습니다.
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/img/03/can-150x150.jpg" alt="">
                    <div class="text">
                        통조림을 활용한 절약과 효율화
                    </div>
                </a>
            </li>
      </ul>
  </aside>
</template>

<script>
export default {

}
</script>

<style scoped>
    .relation ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .relation ul a{
        display: block;
        padding: 5px;
        color: #000000;
        font-size: 14px;
        text-decoration: none;
    }
    .relation ul a:hover{
        text-decoration: underline;
    }
    .relation ul::after{
        content: '';
        display: block;
        clear: both;
    }
    .relation ul li{
        float: left;
        width: 25%;
    }
    .relation img{
        max-width: 100%;
        height: auto;
        border: none;
    }
</style>
<template>
<div class="box4">
    <div class="box4-1">
        <nav class="sidemenu">
            <h1>특집 기사</h1>
            <ul>
                <li><a href="#"><i class="fa fa-caret-right"></i>알기 쉬운 지도 읽기 방법</a></li>
                <li><a href="#"><i class="fa fa-caret-right"></i>처음부터 시작하는 토마토 기르기</a></li>
                <li><a href="#"><i class="fa fa-caret-right"></i>svn 설정 방법</a></li>
                <li><a href="#"><i class="fa fa-caret-right"></i>로지택 연동하는 방법</a></li>
            </ul>
        </nav>
        <nav class="recommend">
            <h1>추천 기사</h1>
            <ul>
                <li>
                    <a href="#">
                        <img src="../assets/img/03/flower.jpg" alt="">
                        <div class="text">
                            처음부터 시작하는 꽃꽃이
                        </div>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/03/old.jpg" alt="">
                        <div class="text">
                            오래된 스마트폰을 충전했더니..
                        </div>
                    </a>
                </li>
            </ul>
        </nav>
    </div>
  <div class="box4-2">
    <nav class="popular">
        <h1>인기 기사</h1>
        <ul>
            <li>
                <a href="#">
                    <img src="../assets/img/03/flower-60x60.jpg" alt="">
                    <div class="text">
                        꽃을 좋아하는 사람들을 위한 포인트
                        <span>외출</span>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/img/03/bag-60x60.jpg" alt="">
                    <div class="text">
                        웹앱 어플리케이션 개발의 기초
                        <span>컴퓨터</span>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/img/03/sea-60x60.jpg" alt="">
                    <div class="text">
                        세계 각지의 바다
                        <span>여행</span>
                    </div>
                </a>
            </li>
        </ul>
    </nav>
  </div>
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

    .recommend img{
        width: 100%;
        height: auto;
        border: none;
        vertical-align: bottom;
    }
    .recommend .text{
        background-color: rgba(0, 0, 0, .5);
        color: #ffffff;
        padding: 5px 10px;
    }

    .recommend ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .recommend li a{
        display: block;
        color: #000000;
        font-size: 15px;
        text-decoration: none;
        margin-bottom: 5px;
    }
    .recommend li a:hover{
        background-color: #e3e3e3;
        opacity: 0.8;
    }
    .recommend h1{
        border-bottom: dotted 2px #666666;
        color: #666666;
    }
    .recommend  {
        margin-bottom: 30px;
    }
    .recommend a{
        position: relative;
    }
    .recommend .text{
        position: absolute;
        bottom: 0;
        left: 0;
        width: 100%;
        box-sizing: border-box;
        -moz-box-sizing: border-box;
        -webkit-box-sizing: border-box;
    }

    .popular ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .popular li a{
        display: block;
        padding: 5px;
        color: #2288bb;
        font-size: 15px;
        text-decoration: none;
        border-bottom: dotted 2px #dddddd;
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
    .popular span{
        display: block;
        color: #666666;
        font-size: 12px;
    }

    @media(min-width:600px) and (max-width: 767px){
        .box4::after{
            content: '';
            display: block;
            clear: both;
        }
        .box4-1{
            float: left;
            width: 50%;
            padding-right: 20px;
            box-sizing: border-box;
            -moz-box-sizing: border-box;
            -webkit-box-sizing: border-box;
        }
        .box4-2{
            float: left;
            width: 50%;
            padding-left: 20px;
            box-sizing: border-box;
            -moz-box-sizing: border-box;
            -webkit-box-sizing: border-box;
        }
    }

    .sidemenu i{
        margin-right: 5px;
        color: #888888;
    }
    
    .popular li a img{
        border: none;
    }
    .popular a::after{
        content: '';
        display: block;
        clear: both;
    }
    .popular img{
        float: left;
        width: 60px;
    }
    .popular .text{
        float: none;
        width: auto;
        margin-left: 60px;
        padding-left: 15px;
    }
</style>
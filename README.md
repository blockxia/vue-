# vue-
vue页面布局
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0">
    <title>私家外卖🐶</title>
    <link rel="stylesheet" href="./css/reset.css">
    <link rel="stylesheet" href="https://cdn.bootcss.com/bootstrap/4.0.0/css/bootstrap.min.css">
</head>
<body>
<div id="app">
    <nav class="navbar navbar-light bg-light justify-content-between">
        <span class="navbar-brand">昌平区北七家宏福...</span>
        <form class="form-inline">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit"><a href="./login.html">登录|注册</a></button>
        </form>
    </nav>
    <div class="content">
        <div class="item"><img src="./images/nav/1.jpg" alt="">甜品饮品</div>
        <div class="item"><img src="./images/nav/2.jpg" alt="">甜品饮品</div>
        <div class="item"><img src="./images/nav/3.jpg" alt="">甜品饮品</div>
        <div class="item"><img src="./images/nav/4.jpg" alt="">甜品饮品</div>
    </div>
    <div class="content2">
        <div class="item"><img src="./images/nav/1.jpg" alt="">甜品饮品</div>
        <div class="item"><img src="./images/nav/2.jpg" alt="">甜品饮</div>
        <div class="item"><img src="./images/nav/3.jpg" alt="">品饮品</div>
        <div class="item"><img src="./images/nav/4.jpg" alt="">甜饮</div>
    </div>
    <div class="shangjia">
        <div class="gray"></div>
        <p>附近商家</p>
        <div class="left">
            <img src="./images/shop/1.jpg" alt="">
        </div>
        <div class="center">
            <h5>锄禾日当午</h5>
            <ul>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_half@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_off@2x.png" alt=""></li>
            </ul>
            <br>
            <span>￥20起送/配送费约￥5</span>
        </div>
        <div class="right">
            <p></p>
        </div>
    </div>
    <div class="shangjia1">
        <div class="gray"></div>
        <div class="left">
            <img src="./images/shop/2.jpg" alt="">
        </div>
        <div class="center">
            <h5>锄禾日当午</h5>
            <ul>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_off@2x.png" alt=""></li>
            </ul>
            <br>
            <span>￥20起送/配送费约￥5</span>
        </div>
        <div class="right">
            <p></p>
        </div>
    </div>
    <div class="shangjia2">
        <div class="gray"></div>
        <div class="left">
            <img src="./images/shop/3.jpg" alt="">
        </div>
        <div class="center">
            <h5>锄禾日当午</h5>
            <ul>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_off@2x.png" alt=""></li>
            </ul>
            <br>
            <span>￥20起送/配送费约￥5</span>
        </div>
        <div class="right">
            <span></span>
        </div>
    </div>
    <div class="shangjia3">
        <div class="gray"></div>
        <div class="left">
            <img src="./images/shop/4.jpg" alt="">
        </div>
        <div class="center">
            <h5>锄禾日当午</h5>
            <ul>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_on@2x.png" alt=""></li>
                <li><img src="./images/stars/star24_off@2x.png" alt=""></li>
            </ul>
            <br>
            <span>￥20起送/配送费约￥5</span>
        </div>
        <div class="right">
            <span></span>
        </div>
    </div>

    <div class="Mfooter">
        <div class="footer">
            <div class="lastfooter "><a  class='active'   href="./index.html">外卖</a></div>
            <div class="lastfooter"><a  href="./saerch.html">搜索</a></div>
            <div class="lastfooter"><a href="./login.html">订单</a></div>
            <div class="lastfooter"><a  href="./saerch.html">我的</a></div>
        </div>
   </div>
</div>
<script type="text/javascript">

let aNodes=document.querySelectorAll('#app > .Mfooter > .footer > .lastfooter > a')
//     console.log(aNodes);
    for (let i = 0; i < aNodes.length; i++) {
         aNodes[i].addEventListener('touchend',function () {
             aNodes[i].className=''
             this.className='active'
            })
     }
</script>
</body>
</html>
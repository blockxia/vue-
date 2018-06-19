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
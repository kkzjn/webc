<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        html,
        body {
            height: 100%;

        }

        .container {
            width: 375px;
            height: 100%;
            /* background-color: rgba(245, 245, 245, 1); */
            margin: 0 auto;
            position: relative;
          
            /* background-color: rgba(245, 245, 245, 1); */
            margin: 0 auto;
            position: relative;
            background: url("./img/矩形\ 1.png") ;
            background-repeat: no-repeat;
        }

        .header {
            width: 375px;
            height: 317px;
            /* background-color: aquamarine; */

            margin-bottom: 82px;

            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .header .user-header {
            width: 68px;
            height: 68px;
            margin-top: 10px;
        }

        .header .title {
            padding: 8px 0;
            font-size: 18px;
            font-weight: 500;
            color: rgba(255, 255, 255, 1);

        }

        .header .signature {
            margin-top: 37px;
        }

        /* .content {

        } */



            .content .item {
                width: 335px;
                height: 68px;
                background: rgba(255, 255, 255, 1);
                margin: 0 auto 12px auto;
                border-radius: 10px;

                box-shadow: 0 4px 8px rgba(92, 92, 92, 0.1);
                display: flex;
                flex-direction: row;
                align-items: center;
                justify-content: space-between;
            }

            .content .item-foot {
                width: 45px;
                /* border: 1px solid blue; */
            }

            .content .item-head {
                width: 66px;
                /* border: 1px solid red; */

                display: flex;
                flex-direction: row;
                justify-content: center;
            }

            .content .item-content {
                width: 224px;
                color: rgba(255, 108, 114, 1);
                font-size: 16px;
                font-weight: 400;
            }

            .footer {
                width: 375PX;
                height: 104px;
                /* background-color: red; */
                position: absolute;
                bottom: 0;
                left: 0;
                background-image: url("./img/矩形\ 1\ \(1\).png");
                background-position: -25px 5px;
                background-repeat: no-repeat;
                /* background-size: 412px px; */
            }


            .nav {
                display: flex;
                flex-direction: row;
                justify-content: space-around;
                align-items: center;
            }

            .nav .item {
                width: 52px;
                height: 52px;
                /* border: 1px solid blue; */

                display: flex;
                flex-direction: column;
                justify-content: space-around;
                align-items: center;
                margin-bottom: 12px;
            }

            .nav .item img {
                width: 22px;
                height: 22px;
            }

            .color-white {
                color: rgba(255, 255, 255, 1);
            }

            .color-gray {
                color: rgba(255, 255, 255, 0.6);
            }
            .footer .goodsCar {
                position: relative;
                width: 70px;
                height: 70px;
                border-radius: 50%;
                background-size: 70px 70px;
                background-image: url("./img/圆形\ 5.png");
                top: -25px;
            }
    </style>
</head>

<body>
    <div class="container">
        <div class="header">
            <span class="title">我的页面</span>
            <img class="user-header" src="./img/分组 3 (2).png" alt="">
            <div class="signature"><span>点击编辑用户个人签名</span><img src="" alt=""></div>
            <div></div>
            <div></div>
        </div>

        <div class="content">
            <div class="item">
                <div class="item-head"><img src="./img/客服.png.png" alt=""></div>
                <p class="item-content">在线客服</p>
                <div class="item-foot"><img src="./img/路径 1.png" alt=""></div>
            </div>
            <div class="item">
                <div class="item-head"><img src="./img/客服.png.png" alt=""></div>
                <p class="item-content">分期付款</p>
                <div class="item-foot"><img src="./img/路径 1.png" alt=""></div>
            </div>
            <div class="item">
                <div class="item-head"><img src="./img/客服.png.png" alt=""></div>
                <p class="item-content">绑定银行卡</p>
                <div class="item-foot"><img src="./img/路径 1.png" alt=""></div>
            </div>
            <div class="item">
                <div class="item-head"><img src="./img/客服.png.png" alt=""></div>
                <p class="item-content">支付明细</p>
                <div class="item-foot"><img src="./img/路径 1.png" alt=""></div>
            </div>
        </div>
        <div style="height: 104px"></div>


        <div class="footer nav">
            <div class="item color-white">
                <img src="./img/分组 3.png" alt="">
                <span>首页</span>
            </div>
            <div class="item color-gray">
                <img src="./img/分组 3.png" alt="">
                <span>首页</span>
            </div>
            <div class="item goodsCar">
                <img src="./img/路径 1 (1).png" alt="">
                <!-- <span>首页</span> -->
            </div>
            <div class="item color-gray">
                <img src="./img/分组 3.png" alt="">
                <span>首页</span>
            </div>
            <div class="item color-gray">
                <img src="./img/分组 3.png" alt="">
                <span>首页</span>
            </div>
        </div>
    </div>
    </div>
</body>

</html>

<!DOCTYPE html>
<html lang="zh-TW">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>品优购-专业的综合网上购物商城</title>
    <meta name="description"
        content="品优购商城-专业的综合网上购物商城,销售家电、数码通讯、电脑、家居百货、服装服饰、母婴、图书、食品等数万个品牌优质商品.便捷、诚信的服务，为您提供愉悦的网上购物体验!">
    <meta name="keywords" content="网上购物,网上商城,手机,笔记本,电脑,MP3,CD,VCD,DV,相机,数码,配件,手表,存储卡,京东">
    <link rel="shortcut icon" href="favicon.ico" />
    <link rel="stylesheet" href="css/base.css">
    <link rel="stylesheet" href="css/common.css">
    <link rel="stylesheet" href="css/index.css">
    <style>
        .w {
    width: 1200px;
    margin: 0 auto;
}
@font-face {
    font-family: 'icomoon';
    src:  url('fonts/icomoon.eot?h3qn5');
    src:  url('fonts/icomoon.eot?h3qn5#iefix') format('embedded-opentype'),
      url('fonts/icomoon.ttf?h3qn5') format('truetype'),
      url('fonts/icomoon.woff?h3qn5') format('woff'),
      url('fonts/icomoon.svg?h3qn5#icomoon') format('svg');
    font-weight: normal;
    font-style: normal;
    font-display: block;
}
/* banner */
.main {
    height: 465px; 
}
.main .banner {
    float: left;
    width: 720px;
    height: 455px;
    margin: 10px 0 10px 218px;
}
.main .banner img {
    width: 100%;
    height: 100%;
}
/* aside */
.main .aside {
    float: left;
    width: 250px;
    height: 376px;
    margin: 10px 0 0 9px;
    border: 1px solid #e4e4e4;
    vertical-align: top;
}
.main .aside .aside_news {
    width: 248px;
    height: 165px;
    border-bottom: 1px solid #e4e4e4;
}
.aside .aside_news h4 {
    width: 250px;
    height: 35px;
    padding-left: 15px;
    line-height: 35px;
    border-bottom: 1px solid #e4e4e4;
    font-size: 14px;
    color: #333333;
}
.aside .aside_news h4::after {
    content: '更多 \e90a';
    margin-left: 109px;
    font-family: 'icomoon';
    font-weight: 400;
    font-size: 12px;
}
.aside_news ul li {
    height: 25px;
    line-height: 25px;
    padding-left: 15px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
.aside_news ul li span {
    margin-right: 5px;
}
.aside .aside_class {
    position: relative;
    width: 250px;
    height: 210px;
}
.aside .aside_class .minus {
    position: absolute;
    width: 12px;
    height: 16px;
    margin-left: 112px;
    background: url(../images/images/images/minus_03.png);
}
.aside_class li{
    float: left;
    width: 62px;
    height: 70px;
    text-align: center;
    border-right: 1px solid #e4e4e4;
    border-bottom: 1px solid #e4e4e4;
}
.aside .aside_class li a {
    display: inline-block;
    width: 62px;
    height: 70px;
}
.aside .aside_class li i {
    display: inline-block;
    width: 24px;
    height: 26px;
    margin: 13px 19px 3px;
}
.aside .aside_class li:nth-child(4n) {
    border-right: 0;
}
.aside .aside_class li:nth-child(n+9) {
    border-bottom: 0;
}
.aside .aside_class li .pic1 {
    background: url(../images/images/icons.png) no-repeat -17px -14px;
}
.aside .aside_class li .pic2 {
    background: url(../images/images/icons.png) no-repeat -79px -14px;
}
.aside .aside_class li .pic3 {
    background: url(../images/images/icons.png) no-repeat -141px -15px;
}
.aside .aside_class li .pic4 {
    background: url(../images/images/icons.png) no-repeat -205px -14px;
}
.aside .aside_class li .pic5 {
    background: url(../images/images/icons.png) no-repeat -16px -87px;
}
.aside .aside_class li .pic6 {
    background: url(../images/images/icons.png) no-repeat -77px -87px;
}
.aside .aside_class li .pic7 {
    background: url(../images/images/icons.png) no-repeat -140px -87px;
}
.aside .aside_class li .pic8 {
    background: url(../images/images/icons.png) no-repeat -205px -87px;
}
.aside .aside_class li .pic9 {
    background: url(../images/images/icons.png) no-repeat -17px -159px;
}
.aside .aside_class li .pic10 {
    background: url(../images/images/icons.png) no-repeat -79px -159px;
}
.aside .aside_class li .pic11 {
    background: url(../images/images/icons.png) no-repeat -141px -159px;
}
.aside .aside_class li .pic12 {
    background: url(../images/images/icons.png) no-repeat -205px -159px;
}
/* aside圖片 */
.aside .aside_bg {
    float: right;
    width: 250px;
    height: 75px;
    margin-top: 4px;
}
.aside .aside_bg a {
    display: block;
    height: 100%;
    width: 100%;
    background: url(../images/images/images/aside_bg_03.png);
}
/* items_box */
.floor {
    position: fixed;
    top: 309px;
    left: 44px;
    width: 66px;
    height: 343px;
}
.floor li {
    height: 32px;
}
.floor li a {
    display: inline-block;
    width: 56px;
    margin: 0 5px;
    line-height: 32px;
    text-align: center;
    border-bottom: 1px solid #ededed;
}
.floor li:hover a {
    background: #c81623;
    color: white;
}
/* 今日推薦 */
.suggest {
    height: 163px;
    margin-top: 10px;
    background-color: #ebebeb;
}
.suggest dl dt,
.suggest dl dd {
    float: left;
}
.suggest dl dt {
    width: 201px;
    height: 163px;
    background-color: #5c5251;
}
.suggest dl dt p {
    color: white;
}
.suggest dl dt p:nth-child(1) {
    width: 57px;
    height: 57px;
    margin: 30px 0 0 67px;
    line-height: 57px;
    font-family: 'icomoon';
    font-size: 60px;
}
.suggest dl dt p:nth-child(2){
    padding:5px 60px 0;
    font-size: 18px;
    font-weight: 700;
    text-align: center;  
}
.suggest dl li {
    float: left;
    width: 1px;
    height: 143px;
    margin-top: 10px;
    background-color: #dddddd;
}
.suggest dl dd[class^="goods"] {
    background-color: #ebebeb;
    width: 249px;
    height: 163px;
}
/* 今日推薦共用區塊 */
.suggest dl .goods1 .lf,
.suggest dl .goods2 .lf,
.suggest dl .goods3 .lf,
.suggest dl .goods4 .lf,
.suggest dl .goods5 .lf {
    float: left;
    width: 107px;
    height: 163px;
}
.suggest dl .goods1 .lf h4,
.suggest dl .goods2 .lf h4,
.suggest dl .goods3 .lf h4,
.suggest dl .goods4 .lf h4,
.suggest dl .goods5 .lf h4 {
    height: 18px;
    margin:20px 0 0 20px;
    font-size: 16px;
    color: #333333;
}
.suggest dl .goods1 .lf p:nth-of-type(1),
.suggest dl .goods2 .lf p:nth-of-type(1),
.suggest dl .goods3 .lf p:nth-of-type(1),
.suggest dl .goods4 .lf p:nth-of-type(1),
.suggest dl .goods5 .lf p:nth-of-type(1) {
    width: 86px;
    height: 18px;
    margin: 12px 0 0 20px;
    background-color: #00a0e8;
    text-align: center;
    line-height: 18px;
    font-size: 14px;
    color: white;
    font-weight: 700;
}
.suggest dl .goods1 .lf p:nth-of-type(2),
.suggest dl .goods2 .lf p:nth-of-type(2),
.suggest dl .goods3 .lf p:nth-of-type(2),
.suggest dl .goods4 .lf p:nth-of-type(2),
.suggest dl .goods5 .lf p:nth-of-type(2) {
    height: 18px;
    margin: 5px 0 0 20px;
    color: #666666;
}
.suggest dl .goods1 .rf,
.suggest dl .goods2 .rf,
.suggest dl .goods3 .rf,
.suggest dl .goods4 .rf,
.suggest dl .goods5 .rf {
    float: left;
    width: 140px;
    height: 163px;
}
.suggest dl .goods2 .lf div,
.suggest dl .goods3 .lf div,
.suggest dl .goods4 .lf div,
.suggest dl .goods5 .lf div {
    width: 57px;
    height: 18px;
    margin: 20px 0 0 22px;
    border-radius: 9px;
    background-color: #5fb200;
    text-align: center;
    line-height: 18px;
    font-size: 14px;
    font-weight: 700;
    color: white;
}
/* 今日推薦商品-1 */
.suggest dl .goods1 .rf {
    background: url(../images/images/guess_goods1.png) no-repeat center center;
}
/* 今日推薦商品-2 */
.suggest dl .goods2 .lf p:nth-of-type(1) {
    background-color: #5fb200;
}
.suggest dl .goods2 .lf div {
    background-color: #5fb200;
}
.suggest dl .goods2 .rf {
    background: url(../images/images/guess_goods2.png) no-repeat center center;
}
/* 今日推薦商品3 */
.suggest dl .goods3 .lf p:nth-of-type(1) {
    width: 70px;
    background-color: #e2162f;
}
.suggest dl .goods3 .lf div {
    background-color: #e2162f;
}
.suggest dl .goods3 .rf {
    background: url(../images/images/guess_goods3.png) no-repeat center center;
}
/* 今日推薦商品4 */
.suggest dl .goods4 .lf p:nth-of-type(1) {
    width: 64px;
    background-color: #0085fb;
}
.suggest dl .goods4 .lf div {
    background-color: #0085fb;
}
.suggest dl .goods4 .rf {
    background: url(../images/images/guess_goods4.png) no-repeat -20px center;
}
/* 猜你喜歡的-上 */
.guesslike {
    height: 265px;
    margin-top: 27px;
}
.guesslike .guess_top {
    height: 32px;
}
.guesslike .guess_top span:nth-of-type(1) {
    float: left;
    line-height: 32px;
    font-size: 18px;
    color: #333333;
}
.guesslike .guess_top span:nth-of-type(2) {
    position: relative;
    float: right;
    margin-right: 45px;
    line-height: 32px;
    color: #666666;
}
.guesslike .guess_top .change_round::after {
    position: absolute;
    margin-left: 10px;
    content: '\e90d';
    font-family: 'icomoon';    
}
.guesslike .guess_top .change_round:hover::after {
    color:  #c81623;
}
.guesslike .guess_bottom {
    height: 233px;
    border: 1px solid #ededed;
    background-color: white;
}
.guess_bottom ul .guess_goods1,
.guess_bottom ul .guess_goods2,
.guess_bottom ul .guess_goods3,
.guess_bottom ul .guess_goods4,
.guess_bottom ul .guess_goods5,
.guess_bottom ul .guess_goods6 {
    float: left;
    width: 199.6px;
}
.guess_bottom ul .guess_goods1 div:nth-of-type(1),
.guess_bottom ul .guess_goods2 div:nth-of-type(1), 
.guess_bottom ul .guess_goods3 div:nth-of-type(1),
.guess_bottom ul .guess_goods4 div:nth-of-type(1),
.guess_bottom ul .guess_goods5 div:nth-of-type(1),
.guess_bottom ul .guess_goods6 div:nth-of-type(1) {
    height: 160px;
}
.guess_bottom ul .guess_goods1 div:nth-of-type(2),
.guess_bottom ul .guess_goods2 div:nth-of-type(2), 
.guess_bottom ul .guess_goods3 div:nth-of-type(2), 
.guess_bottom ul .guess_goods4 div:nth-of-type(2), 
.guess_bottom ul .guess_goods5 div:nth-of-type(2), 
.guess_bottom ul .guess_goods6 div:nth-of-type(2) {
    height: 63px;
    margin-bottom: 10px;
    border-right: 1px solid #ededed;
}
.guess_bottom ul .guess_goods1 h4,
.guess_bottom ul .guess_goods2 h4,
.guess_bottom ul .guess_goods3 h4,
.guess_bottom ul .guess_goods4 h4,
.guess_bottom ul .guess_goods5 h4,
.guess_bottom ul .guess_goods6 h4 {
    width: 120px;
    height: 35px;
    margin-left: 35px;
    line-height: 18px;;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
}
.guess_bottom ul .guess_goods1 span,
.guess_bottom ul .guess_goods2 span,
.guess_bottom ul .guess_goods3 span,
.guess_bottom ul .guess_goods4 span,
.guess_bottom ul .guess_goods5 span,
.guess_bottom ul .guess_goods6 span {
    padding-left: 35px;
    line-height: 35px;
    font-size: 18px;
    font-weight: 700;
    color: red;
}
.guesslike .guess_bottom ul .guess_goods1 div:nth-of-type(1) {
    background: url(../images/images/like_goods1.png) no-repeat center center;
}
.guesslike .guess_bottom ul .guess_goods2 div:nth-of-type(1) {
    background: url(../images/images/like_goods2.png) no-repeat center center;
}
.guesslike .guess_bottom ul .guess_goods3 div:nth-of-type(1) {
    background: url(../images/images/like_goods3.png) no-repeat center center;
}
.guesslike .guess_bottom ul .guess_goods4 div:nth-of-type(1) {
    background: url(../images/images/like_goods4.png) no-repeat center center;
}
.guesslike .guess_bottom ul .guess_goods5 div:nth-of-type(1) {
    background: url(../images/images/like_goods5.png) no-repeat center center;
}
.guesslike .guess_bottom ul .guess_goods6 div:nth-of-type(1) {
    background: url(../images/images/like_goods6.png) no-repeat center center;
}   
/* 有趣區 */
.fun {
    height: 434px;
    margin-top: 28px;
    background-color: #ffffff;
}
.fun .fun_top {
    height: 28px;
    font-size: 18px;
    color: #333333;
}
.fun .fun_bottom {
    height: 407px;
}
.fun_bottom .fun_box1,
.fun_bottom .fun_box2,
.fun_bottom .fun_box3,
.fun_bottom .fun_box4 {
    float: left;
}
.fun_bottom .fun_box1 {
    position: relative;
    width: 402px;
    height: 407px;
    background: #b8bddd url(../images/images/fun_box1.png) no-repeat 124px 112px;
}
.fun_bottom .fun_box1 a {
    display: inline-block;
    width: 402px;
    height: 407px;
}
.fun_bottom .fun_box1 h4 {
    position: absolute;
    top: 24px;
    left: 19px;
    width: 135px;
    height: 44px;
    font-size: 18px;
    color: #3b468d;
}
.fun_bottom .fun_box1 h4 p {
   font-size: 16px;
}
.fun_bottom .fun_box2 .content_1,
.fun_bottom .fun_box2 .content_2,
.fun_bottom .fun_box3 .content_3,
.fun_bottom .fun_box3 .content_4,
.fun_bottom .fun_box3 .content_5  {
    position: relative;
}
.fun_bottom .fun_box2 .content_1 h4,
.fun_bottom .fun_box2 .content_2 h4,
.fun_bottom .fun_box3 .content_3 h4,
.fun_bottom .fun_box3 .content_4 h4,
.fun_bottom .fun_box3 .content_5 h4 {
    position: absolute;
    height: 16px;
    line-height: 16px;
    font-size: 16px;
    color: #333333;
}
.fun_bottom .fun_box2 .content_1 p,
.fun_bottom .fun_box2 .content_2 p,
.fun_bottom .fun_box3 .content_3 p,
.fun_bottom .fun_box3 .content_4 p,
.fun_bottom .fun_box3 .content_5 p {
    position: absolute;
    font-weight: 700;
    color: #333333;
}
.fun_bottom .fun_box2 .content_1 p span,
.fun_bottom .fun_box2 .content_2 p span,
.fun_bottom .fun_box3 .content_3 p span,
.fun_bottom .fun_box3 .content_4 p span,
.fun_bottom .fun_box3 .content_5 p span {
    color: red;
}
.fun_bottom .fun_box2 {
    width: 227px;
    height: 407px;
    border: 1px solid #ededed;
    border-left: 0;
    background-color: #ffffff;
}
.fun_bottom .fun_box2 .title {
    width: 190px;
    height: 40px;
    margin-left: 19px;
    border-bottom: 1px dashed #ededed;
    text-align: center;
    line-height: 40px;
    font-size: 14px;
    font-weight: 700;
    color: #333333;
}
.fun_bottom .fun_box2 .content_1 {
    width: 227px;
    height: 207px;
    border-bottom: 1px solid #ededed;
    background: url(../images/images/fun_box2-1.png) no-repeat 95px 28px;
}
.fun_bottom .fun_box2 .content_1 a {
    display: inline-block;
    width: 227px;
    height: 207px;
}
.fun_bottom .fun_box2 .content_1 h4 {
    top: 68px;
    left: 10px;
}
.fun_bottom .fun_box2 .content_1 p {
    top: 100px;
    left: 10px;
}
.fun_bottom .fun_box2 .content_2{
    width: 227px;
    height: 159px;
    background: url(../images/images/fun_box2-3.png) no-repeat 103px 12px ;
}
.fun_bottom .fun_box2 .content_2 a{
    display: inline-block;
    width: 227px;
    height: 159px;
}
.fun_bottom .fun_box2 .content_2 h4 {
    top: 49px; 
    left: 10px;
}
.fun_bottom .fun_box2 .content_2 p {
    top: 80px; 
    left: 10px;
}
.fun_bottom .fun_box3 {
    width: 405px;
    height: 407px;
    background-color: #f7f7f7;
    border: 1px solid  #ededed;
    border-left: 0;
}
.fun_bottom .fun_box3 .title {
    width: 365px;
    height: 40px;
    margin-left: 19px;
    border-bottom: 1px solid #ededed;
    text-align: center;
    line-height: 40px;
    font-size: 14px;
    font-weight: 700;
    color: #333333;
}
.fun_bottom .fun_box3 .content_3 {
    width: 405px;
    height: 207px;
    background: url(../images/images/fun_box3-1.png) no-repeat 198px 33px;
    border-bottom: 1px solid  #ededed;
}
.fun_bottom .fun_box3 .content_3 a {
    display: inline-block;
    width: 405px;
    height: 207px;
}
.fun_bottom .fun_box3 .content_3 h4 {
    top: 73px;
    left: 52px;
}
.fun_bottom .fun_box3 .content_3 p {
    top: 104px;
    left: 52px;
}
.fun_bottom .fun_box3 .content_4 {
    float: left;
    width: 201px;
    height: 159px;
    background: url(../images/images/fun_box4-1.png) no-repeat 97px 28px;
    border-right: 1px solid  #ededed;
}
.fun_bottom .fun_box3 .content_4 a {
    display: inline-block;
    width: 201px;
    height: 159px;
}
.fun_bottom .fun_box3 .content_4 h4 {
    top: 49px;
    left: 12px;
}
.fun_bottom .fun_box3 .content_4 p {
    top: 80px;
    left: 12px;
}
.fun_bottom .fun_box3 .content_5 {
    float: left;
    width: 202px;
    height: 159px;
    background: url(../images/images/fun_box-5-1.png) no-repeat 82px 22px;
}
.fun_bottom .fun_box3 .content_5 a {
    display: inline-block;
    width: 202px;
    height: 159px;
}
.fun_bottom .fun_box3 .content_5 h4 {
    top: 49px;
    left: 21px;
}
.fun_bottom .fun_box3 .content_5 p {
    top: 80px;
    left: 21px;
}
.fun_bottom .fun_box4 {
    width: 166px;
    height: 407px;
    padding-left: 6px;
    background-color: #ffffff;
    border: 1px solid #ededed;
    border-left: 0;
}
.fun_bottom .fun_box4 li {
    float: left;
    width: 79px;
    height: 58px;
    border-bottom: 1px dashed #ededed;
    background-color: red;
}
.fun_bottom .fun_box4 li a {
    display: inline-block;
    width: 79px;
    height: 58px;
}
.fun_bottom .fun_box4 li:nth-child(2n-1) {
    border: 1px dashed #ededed;
    border-left: 0;
    border-top: 0;
}
.fun_bottom .fun_box4 li:nth-child(1) {
    background: url(../images/images/images/5-1_03.png);
}
.fun_bottom .fun_box4 li:nth-child(2) {
    background: url(../images/images/images/5-2_03.png);
}
.fun_bottom .fun_box4 li:nth-child(3) {
    background: url(../images/images/images/5-3_07.png);
}
.fun_bottom .fun_box4 li:nth-child(4) {
    background: url(../images/images/images/5-4_03.png);
}
.fun_bottom .fun_box4 li:nth-child(5) {
    background: url(../images/images/images/5-5_03.png);
}
.fun_bottom .fun_box4 li:nth-child(6) {
    background: url(../images/images/images/5-6_03.png);
}
.fun_bottom .fun_box4 li:nth-child(7) {
    background: url(../images/images/images/5-7_03.png);
}
.fun_bottom .fun_box4 li:nth-child(8) {
    background: url(../images/images/images/5-8_03.png);
}
.fun_bottom .fun_box4 li:nth-child(9) {
    background: url(../images/images/images/5-9_03.png);
}
.fun_bottom .fun_box4 li:nth-child(10) {
    background: url(../images/images/images/5-10_03.png);
}
.fun_bottom .fun_box4 li:nth-child(11) {
    background: url(../images/images/images/5-11_03.png);
}
.fun_bottom .fun_box4 li:nth-child(12) {
    background: url(../images/images/images/5-12_03.png);
}
.fun_bottom .fun_box4 li:nth-child(13) {
    background: url(../images/images/images/5-13_03.png);
}
.fun_bottom .fun_box4 li:nth-child(14) {
    background: url(../images/images/images/5-14_03.png);
}
/* 家用電器 */
.machine {
    height: 393px;
    margin-top: 25px;
}
.machine .machine_top {
    height: 32px;
    border-bottom: 2px solid #c81623;
}
.machine .machine_top span {
    float: left;
    height: 32px;
    line-height: 32px;
    font-size: 18px;
    color: #c81623;
}
.machine .machine_top ul li:nth-child(2n-1) {
    float: right;
    line-height: 32px;    
}
.machine .machine_top ul li:nth-child(2n) {
    float: right;
    width: 1px;
    height: 14px;
    margin: 9px 11px 0;
    background-color: #999999;
}
.machine .machine_top ul li:first-child {
    margin-right: 10px;
}
.machine .machine_bottom {
    height: 360px;
    border-bottom: 1px solid #ededed;
    border-right: 1px solid #ededed;
}
.machine .machine_bottom .machine_box1 {
    float: left;
    width: 210px;
    height: 360px;
    background-color: #f9f9f9;
}
.machine_bottom .machine_box1 .machine_items {
    width: 186px;
    height: 100px;
    margin: 0 12px;
}
.machine_bottom .machine_box1 .machine_items li {
    float: left;
    width: 87px;
    height: 32px;
    border-bottom: 1px solid #ededed;
    text-align: center;
    line-height: 32px;
}
.machine_bottom .machine_box1 .machine_items li a {
    display: block;
}
.machine_bottom .machine_box1 .machine_items li:nth-child(2n) {
    margin-left: 12px;
}
.machine_bottom .machine_box1 .machine_pic1 {
    position: relative;
    height: 262px;
    background: url(../images/images/machine_pic1.png) no-repeat 28px 81px;    
}
.machine_bottom .machine_box1 .machine_pic1 a {
    display: block;
    height: 262px;
}
.machine_bottom .machine_box1 .machine_pic1 h4,
.machine_bottom .machine_box1 .machine_pic1 p {
    text-align: center;
    color: #c81623;
    font-size: 12px;
}
.machine_bottom .machine_box1 .machine_pic1 h4 {
    position: absolute;
    top: 25px;
    left: 51px;
    font-size: 18px;
}
.machine_bottom .machine_box2 {
    position: relative;
    float: left;
    width: 329px;
    height: 359px;
    background: #aed6d8 url(../images/images/machine_box2.png) no-repeat 52px 112px;
}
.machine_bottom .machine_box2 h4,
.machine_bottom .machine_box2 p {
    color: #066c7d;
    font-size: 16px;
}
.machine_bottom .machine_box2 h4 {
    position: absolute;
    top: 38px;
    left: 31px;
    font-size: 18px;
}
.machine_bottom .machine_box2 li {
    position: absolute;
    width: 10px;
    height: 10px;
    border-radius: 5px;
    background-color: #3e3e3e;
}
.machine_bottom .machine_box2 li:nth-of-type(1){
    top: 334px;
    left: 142px;
    background-color: white;
}
.machine_bottom .machine_box2 li:nth-of-type(2){
    top: 334px;
    left: 159px;
}
.machine_bottom .machine_box2 li:nth-of-type(3){
    top: 334px;
    left: 177px;
}
.machine_bottom .machine_box2 a{
    display: block;
    width: 329px;
    height: 359px;
}
.machine_bottom .machine_box3 {
    float: left;
    width: 218px;
    height: 359px;
    border-right: 1px solid #ededed;
}
.machine_bottom .machine_box3 .box3_1 {
    position: relative;
    width: 216px;
    height: 180px;
    border-bottom: 1px solid #ededed;
    background: url(../images/images/machine_box3-1.png) no-repeat 77px 99px;
}
.machine_bottom .machine_box3 .box3_1 a {
    display: block;
    width: 216px;
    height: 180px;
}
.machine_bottom .machine_box3 .box3_2 {
    position: relative;
    height: 179px;
    background: url(../images/images/machine_box3-2.png) no-repeat 61px 74px;
}
.machine_bottom .machine_box3 .box3_2 a {
    display: block;
    height: 179px;
}
.machine_bottom .machine_box3 .box3_1 h4,
.machine_bottom .machine_box3 .box3_2 h4, 
.machine_bottom .machine_box5 .box5_1 h4,
.machine_bottom .machine_box5 .box5_2 h4 {
    position: absolute;
    top: 24px;
    left: 19px;
    font-size: 16px;
    color: #000000;
}
.machine_bottom .machine_box3 .box3_1 p,
.machine_bottom .machine_box3 .box3_2 p, 
.machine_bottom .machine_box5 .box5_1 p,
.machine_bottom .machine_box5 .box5_2 p {
    font-size: 14px;
    color: #e60012;
}
.machine_bottom .machine_box4 {
    position: relative;
    float: left;
    width: 220px;
    height: 359px;
    border-right: 1px solid #ededed;
    background: url(../images/images/machine_box4-1.png) no-repeat 24px 194px;
}
.machine_bottom .machine_box4 a {
    display:block;
    width: 220px;
    height: 359px;
}
.machine_bottom .machine_box4 h4 {
    position: absolute;
    top: 70px;
    left: 30px;
    text-align: center;
    font-size: 18px;
    color: #000000;
}
.machine_bottom .machine_box4 p {
    font-size: 16px;
    color: #999999;
}
.machine_bottom .machine_box5 {
    float: left;
    width: 222px;
    height: 359px;
}
.machine_bottom .machine_box5 .box5_1 {
    position: relative;
    height: 180px;
    border-bottom: 1px solid #ededed;
    background: url(../images/images/machine_box5-1.png) no-repeat 81px 90px;
}
.machine_bottom .machine_box5 .box5_1 a {
    display: block;
    height: 180px;
}
.machine_bottom .machine_box5 .box5_2 {
    position: relative;
    height: 179px;
    background: url(../images/images/machine_box5-2.png) no-repeat 102px 36px;
}
.machine_bottom .machine_box5 .box5_2 a{
    display: block;
    height: 179px;
}
/* machine brand */
.machine_brand {
    height: 65px;
    margin-top: 20px;
    background-color: #f7f7f7;
}
.machine_brand ul li {
    float: left;
    height: 41px;
    width: 120px;
    margin-top: 12px;
    border-right: 1px dashed #ededed;
}
.machine_brand ul li a {
    display: block;
    height: 41px;
}
.machine_brand ul li:nth-child(1) {
    background: url(../images/images/images/machine_brand1_03.png);
}
.machine_brand ul li:nth-child(2) {
    background: url(../images/images/images/machine_brand2_03.png);
}
.machine_brand ul li:nth-child(3) {
    background: url(../images/images/images/machine_brand3_03.png);
}
.machine_brand ul li:nth-child(4) {
    background: url(../images/images/images/machine_brand4_03.png);
}
.machine_brand ul li:nth-child(5) {
    background: url(../images/images/images/machine_brand5_03.png);
}
.machine_brand ul li:nth-child(6) {
    background: url(../images/images/images/machine_brand6_03.png);
}
.machine_brand ul li:nth-child(7) {
    background: url(../images/images/images/machine_brand7_03.png);
}
.machine_brand ul li:nth-child(8) {
    background: url(../images/images/images/marchine_brand8_03.png);
}
.machine_brand ul li:nth-child(9) {
    background: url(../images/images/images/machine_brand9_03.png);
}
.machine_brand ul li:nth-child(10) {
    background: url(../images/images/images/machine_brand10_03.png);
}
/* 手機通訊 */
.cellphone {
    height: 393px;
    margin-top: 25px;
}
.cellphone .cellphone_top {
    height: 32px;
    border-bottom: 2px solid #c81623;
}
.cellphone .cellphone_top span {
    float: left;
    height: 32px;
    line-height: 32px;
    font-size: 18px;
    color: #c81623;
}
.cellphone .cellphone_top ul li:nth-child(2n-1) {
    float: right;
    line-height: 32px;    
}
.cellphone .cellphone_top ul li:nth-child(2n) {
    float: right;
    width: 1px;
    height: 14px;
    margin: 9px 11px 0;
    background-color: #999999;
}
.cellphone .cellphone_top ul li:first-child {
    margin-right: 10px;
}
.cellphone .cellphone_bottom {
    height: 360px;
    border-bottom: 1px solid #ededed;
    border-right: 1px solid #ededed;
}
.cellphone .cellphone_bottom .cellphone_box1 {
    float: left;
    width: 210px;
    height: 360px;
    background-color: #f9f9f9;
}
.cellphone_bottom .cellphone_box1 .cellphone_items {
    width: 186px;
    height: 100px;
    margin: 0 12px;
}
.cellphone_bottom .cellphone_box1 .cellphone_items li {
    float: left;
    width: 87px;
    height: 32px;
    border-bottom: 1px solid #ededed;
    text-align: center;
    line-height: 32px;
}
.cellphone_bottom .cellphone_box1 .cellphone_items li:nth-child(2n) {
    margin-left: 12px;
}
.cellphone_bottom .cellphone_box1 .cellphone_items li a {
    display: block;
}
.cellphone_bottom .cellphone_box1 .cellphone_pic1 {
    position: relative;
    height: 262px;
    background: url(../images/images/cellphone\ 1.png) no-repeat 41px 81px;    
}
.cellphone_bottom .cellphone_box1 .cellphone_pic1 a {
    display: block;
    height: 262px;
}
.cellphone_bottom .cellphone_box1 .cellphone_pic1 h4,
.cellphone_bottom .cellphone_box1 .cellphone_pic1 p {
    text-align: center;
    color: #c81623;
    font-size: 12px;
}
.cellphone_bottom .cellphone_box1 .cellphone_pic1 h4 {
    position: absolute;
    top: 25px;
    left: 30px;
    font-size: 18px;
}
.cellphone_bottom .cellphone_box2 {
    position: relative;
    float: left;
    width: 329px;
    height: 359px;
    background: #c6e8b6 url(../images/images/images/cellphonebox2-1_07.png) no-repeat 95px 118px;
}
.cellphone_bottom .cellphone_box2 h4,
.cellphone_bottom .cellphone_box2 p {
    color: #066c7d;
    font-size: 16px;
}
.cellphone_bottom .cellphone_box2 h4 {
    position: absolute;
    top: 38px;
    left: 31px;
    font-size: 18px;
}
.cellphone_bottom .cellphone_box2 li {
    position: absolute;
    width: 10px;
    height: 10px;
    border-radius: 5px;
    background-color: #3e3e3e;
}
.cellphone_bottom .cellphone_box2 li:nth-of-type(1){
    top: 334px;
    left: 142px;
    background-color: white;
}
.cellphone_bottom .cellphone_box2 li:nth-of-type(2){
    top: 334px;
    left: 159px;
}
.cellphone_bottom .cellphone_box2 li:nth-of-type(3){
    top: 334px;
    left: 177px;
}
.cellphone_bottom .cellphone_box2 a{
    display: block;
    width: 329px;
    height: 359px;
}
.cellphone_bottom .cellphone_box3 {
    float: left;
    width: 218px;
    height: 359px;
    border-right: 1px solid #ededed;
}
.cellphone_bottom .cellphone_box3 .box3_1 {
    position: relative;
    width: 216px;
    height: 180px;
    border-bottom: 1px solid #ededed;
    background: url(../images/images/cellphonebox3-1.png) no-repeat 120px 81px;
}
.cellphone_bottom .cellphone_box3 .box3_1 a {
    display: block;
    width: 216px;
    height: 180px;
}
.cellphone_bottom .cellphone_box3 .box3_2 {
    position: relative;
    height: 179px;
    background: url(../images/images/cellphonebox3-2.png) no-repeat 106px 70px;
}
.cellphone_bottom .cellphone_box3 .box3_2 a {
    display: block;
    height: 179px;
}
.cellphone_bottom .cellphone_box3 .box3_1 h4,
.cellphone_bottom .cellphone_box3 .box3_2 h4, 
.cellphone_bottom .cellphone_box5 .box5_1 h4,
.cellphone_bottom .cellphone_box5 .box5_2 h4 {
    position: absolute;
    top: 24px;
    left: 19px;
    font-size: 16px;
    color: #000000;
}
.cellphone_bottom .cellphone_box3 .box3_1 p,
.cellphone_bottom .cellphone_box3 .box3_2 p, 
.cellphone_bottom .cellphone_box5 .box5_1 p,
.cellphone_bottom .cellphone_box5 .box5_2 p {
    font-size: 14px;
    color: #e60012;
}
.cellphone_bottom .cellphone_box4 {
    position: relative;
    float: left;
    width: 220px;
    height: 359px;
    border-right: 1px solid #ededed;
    background: url(../images/images/cellphonebox4-1.png) no-repeat 48px 156px;
}
.cellphone_bottom .cellphone_box4 a {
    display:block;
    width: 220px;
    height: 359px;
}
.cellphone_bottom .cellphone_box4 h4 {
    position: absolute;
    top: 70px;
    left: 30px;
    text-align: center;
    font-size: 18px;
    color: #000000;
}
.cellphone_bottom .cellphone_box4 p {
    font-size: 16px;
    color: #999999;
}
.cellphone_bottom .cellphone_box5 {
    float: left;
    width: 222px;
    height: 359px;
}
.cellphone_bottom .cellphone_box5 .box5_1 {
    position: relative;
    height: 180px;
    border-bottom: 1px solid #ededed;
    background: url(../images/images/cellphonebox5-1.png) no-repeat 130px 77px;
}
.cellphone_bottom .cellphone_box5 .box5_1 a {
    display: block;
    height: 180px;
}
.cellphone_bottom .cellphone_box5 .box5_2 {
    position: relative;
    height: 179px;
    background: url(../images/images/cellphonebox5-2.png) no-repeat 115px 69px;
}
.cellphone_bottom.cellphone_box5 .box5_2 a{
    display: block;
    height: 179px;
}
/* cellphone brand */
.cellphone_brand {
    height: 65px;
    margin-top: 20px;
    background-color: #f7f7f7;
}
.cellphone_brand ul li {
    float: left;
    height: 41px;
    width: 120px;
    margin-top: 12px;
    border-right: 1px dashed #ededed;
}
.cellphone_brand ul li a {
    display: block;
    height: 41px;
}
.cellphone_brand ul li:nth-child(1) {
    background: url(../images/images/images/images/cellphone_brand1_07.png);
}
.cellphone_brand ul li:nth-child(2) {
    background: url(../images/images/images/images/cellphone_brond2_07.png);
}
.cellphone_brand ul li:nth-child(3) {
    background: url(../images/images/images/images/cellphone_brand3_07.png);
}
.cellphone_brand ul li:nth-child(4) {
    background: url(../images/images/images/images/cellphone_brand4_07.png);
}
.cellphone_brand ul li:nth-child(5) {
    background: url(../images/images/images/images/cellphone_brand5_07.png);
}
.cellphone_brand ul li:nth-child(6) {
    background: url(../images/images/images/images/cellphone_brand6_07.png);
}
.cellphone_brand ul li:nth-child(7) {
    background: url(../images/images/images/images/cellphone_brand7_07.png);
}
.cellphone_brand ul li:nth-child(8) {
    background: url(../images/images/images/images/cellphone_brand8_07.png);
}
.cellphone_brand ul li:nth-child(9) {
    background: url(../images/images/images/images/cellphone_brand9_07.png);
}
.cellphone_brand ul li:nth-child(10) {
    background: url(../images/images/images/images/cellphone_brand10_07.png);
}
/* computer */
.computer {
    height: 393px;
    margin-top: 25px;
}
.computer .computer_top {
    height: 32px;
    border-bottom: 2px solid #c81623;
}
.computer .computer_top span {
    float: left;
    height: 32px;
    line-height: 32px;
    font-size: 18px;
    color: #c81623;
}
.computer .computer_top ul li:nth-child(2n-1) {
    float: right;
    line-height: 32px;    
}
.computer .computer_top ul li:nth-child(2n) {
    float: right;
    width: 1px;
    height: 14px;
    margin: 9px 11px 0;
    background-color: #999999;
}
.computer .computer_top ul li:first-child {
    margin-right: 10px;
}
.computer .computer_bottom {
    height: 360px;
    border-bottom: 1px solid #ededed;
    border-right: 1px solid #ededed;
}
.computer .computer_bottom .computer_box1 {
    float: left;
    width: 210px;
    height: 360px;
    background-color: #f9f9f9;
}
.computer_bottom .computer_box1 .computer_items {
    width: 186px;
    height: 100px;
    margin: 0 12px;
}
.computer_bottom .computer_box1 .computer_items li {
    float: left;
    width: 87px;
    height: 32px;
    border-bottom: 1px solid #ededed;
    text-align: center;
    line-height: 32px;
}
.computer_bottom .computer_box1 .computer_items li a {
    display: block;
}
.computer_bottom .computer_box1 .computer_items li:nth-child(2n) {
    margin-left: 12px;
}
.computer_bottom .computer_box1 .computer_pic1 {
    position: relative;
    height: 262px;
    background: url(../images/images/computer_box1.png) no-repeat 23px 100px;    
}
.computer_bottom .computer_box1 .computer_pic1 a {
    display: block;
    height: 262px;
}
.computer_bottom .computer_box1 .computer_pic1 h4,
.computer_bottom .computer_box1 .computer_pic1 p {
    text-align: center;
    color: #c81623;
    font-size: 12px;
}
.computer_bottom .computer_box1 .computer_pic1 h4 {
    position: absolute;
    top: 23px;
    left: 31px;
    font-size: 18px;
}
.computer_bottom .computer_box2 {
    position: relative;
    float: left;
    width: 329px;
    height: 359px;
    background: #d7aac9 url(../images/images/computer_box2.png) no-repeat 82px 136px;
}
.computer_bottom .computer_box2 h4,
.computer_bottom .computer_box2 p {
    color: #874d75;
    font-size: 16px;
}
.computer_bottom .computer_box2 h4 {
    position: absolute;
    top: 33px;
    left: 33px;
    font-size: 18px;
}
.computer_bottom .computer_box2 li {
    position: absolute;
    width: 10px;
    height: 10px;
    border-radius: 5px;
    background-color: #3e3e3e;
}
.computer_bottom .computer_box2 li:nth-of-type(1){
    top: 334px;
    left: 142px;
    background-color: white;
}
.computer_bottom .computer_box2 li:nth-of-type(2){
    top: 334px;
    left: 159px;
}
.computer_bottom .computer_box2 li:nth-of-type(3){
    top: 334px;
    left: 177px;
}
.computer_bottom .computer_box2 a{
    display: block;
    width: 329px;
    height: 359px;
}
.computer_bottom .computer_box3 {
    float: left;
    width: 218px;
    height: 359px;
    border-right: 1px solid #ededed;
}
.computer_bottom .computer_box3 .box3_1 {
    position: relative;
    width: 216px;
    height: 180px;
    border-bottom: 1px solid #ededed;
    background: url(../images/images/computer_box3-1.png) no-repeat 75px 81px;
}
.computer_bottom .computer_box3 .box3_1 a {
    display: block;
    width: 216px;
    height: 180px;
}
.computer_bottom .computer_box3 .box3_2 {
    position: relative;
    height: 179px;
    background: url(../images/images/computer_box3-2.png) no-repeat 74px 100px;
}
.computer_bottom .computer_box3 .box3_2 a {
    display: block;
    height: 179px;
}
.computer_bottom .computer_box3 .box3_1 h4,
.computer_bottom .computer_box3 .box3_2 h4, 
.computer_bottom .computer_box5 .box5_1 h4,
.computer_bottom .computer_box5 .box5_2 h4 {
    position: absolute;
    top: 24px;
    left: 19px;
    font-size: 16px;
    color: #000000;
}
.computer_bottom .computer_box3 .box3_1 p,
.computer_bottom .computer_box3 .box3_2 p, 
.computer_bottom .computer_box5 .box5_1 p,
.computer_bottom .computer_box5 .box5_2 p {
    font-size: 14px;
    color: #e60012;
}
.computer_bottom .computer_box4 {
    position: relative;
    float: left;
    width: 220px;
    height: 359px;
    border-right: 1px solid #ededed;
    background: url(../images/images/computer_box4.png) no-repeat 55px 183px;
}
.computer_bottom .computer_box4 a {
    display:block;
    width: 220px;
    height: 359px;
}
.computer_bottom .computer_box4 h4 {
    position: absolute;
    top: 67px;
    left: 40px;
    text-align: center;
    font-size: 18px;
    color: #000000;
}
.computer_bottom .computer_box4 p {
    font-size: 16px;
    color: #999999;
}
.computer_bottom .computer_box5 {
    float: left;
    width: 222px;
    height: 359px;
}
.computer_bottom .computer_box5 .box5_1 {
    position: relative;
    height: 180px;
    border-bottom: 1px solid #ededed;
    background: url(../images/images/machine_box5-1.png) no-repeat 81px 90px;
}
.computer_bottom .computer_box5 .box5_1 a {
    display: block;
    height: 180px;
}
.computer_bottom .computer_box5 .box5_2 {
    position: relative;
    height: 179px;
    background: url(../images/images/computer_box5-2.png) no-repeat 94px 76px;
}
.computer_bottom .computer_box5 .box5_2 a{
    display: block;
    height: 179px;
}
/* computer brand */
.computer_brand {
    height: 65px;
    margin-top: 20px;
    background-color: #f7f7f7;
}
.computer_brand ul li {
    float: left;
    height: 41px;
    width: 120px;
    margin-top: 12px;
    border-right: 1px dashed #ededed;
}
.computer_brand ul li a {
    display: block;
    height: 41px;
}
.computer_brand ul li:nth-child(1) {
    background: url(../images/images/images/images/computer_brand1_03.png);
}
.computer_brand ul li:nth-child(2) {
    background: url(../images/images/images/images/computer2_03.png);
}
.computer_brand ul li:nth-child(3) {
    background: url(../images/images/images/images/computer_brand3_03.png);
}
.computer_brand ul li:nth-child(4) {
    background: url(../images/images/images/images/computer_brand4_03.png);
}
.computer_brand ul li:nth-child(5) {
    background: url(../images/images/images/images/computer_brand5_03.png);
}
.computer_brand ul li:nth-child(6) {
    background: url(../images/images/images/images/computer_brand6_03.png);
}
.computer_brand ul li:nth-child(7) {
    background: url(../images/images/images/images/computer_brand7_03.png);
}
.computer_brand ul li:nth-child(8) {
    background: url(../images/images/images/images/computer_brand8_03.png);
}
.computer_brand ul li:nth-child(9) {
    background: url(../images/images/images/images/computer_brand9_03.png);
}
.computer_brand ul li:nth-child(10) {
    background: url(../images/images/images/images/computer_brand10_03.png);
}
/* 熱門瘋搶 */
.hot {
    height: 316px;
    margin-top: 27px;
}
.hot .hot_top {
    height: 33px;
    font-size: 18px;
    color: #333333;
}
.hot .hot_bottom {
    height: 283px;
    border: 1px solid #ededed;
}
.hot .hot_bottom .hot_box1,
.hot .hot_bottom .hot_box2,
.hot .hot_bottom .hot_box3 {
    float: left;
}
.hot .hot_bottom .hot_box1 {
    position: relative;
    width: 240px;
    height: 281px;
    border-right: 1px solid #ededed;
    background: url(../images/images/images/hot_box1_03.png) no-repeat 40px 47px;
}
.hot .hot_bottom .hot_box1 h4 p,
.hot .hot_bottom .hot_box2 .hot_box2_1 h4 p,
.hot .hot_bottom .hot_box2 .hot_box2_2 h4 p,
.hot .hot_bottom .hot_box2 .hot_box2_3 h4 p,
.hot .hot_bottom .hot_box2 .hot_box2_4 h4 p,
.hot .hot_bottom .hot_box2 .hot_box2_5 h4 p,
.hot .hot_bottom .hot_box2 .hot_box2_6 h4 p {
    font-size: 16px;
    color: red;
}
.hot .hot_bottom .hot_box1 h4 {
    position: absolute;
    top: 210px;
    left: 28px;
    width: 195px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    font-size: 12px;
    color: #333333;
}
.hot .hot_bottom .hot_box2 {
    width: 662px;
    height: 281px;
}
.hot_bottom .hot_box2 .hot_box2_1,
.hot_bottom .hot_box2 .hot_box2_2,
.hot_bottom .hot_box2 .hot_box2_3,
.hot_bottom .hot_box2 .hot_box2_4,
.hot_bottom .hot_box2 .hot_box2_5,
.hot_bottom .hot_box2 .hot_box2_6 {
    position: relative;
    float: left;
    width: 220px;
    height: 140.5px;
}
.hot_bottom .hot_box2 .hot_box2_1 {
    background: url(../images/images/images/hot_box2-1_03.png) no-repeat 15px 35px;
    border: 1px solid #ededed;
    border-top: 0;
    border-left: 0;
}
.hot_bottom .hot_box2 .hot_box2_1 h4 {
    top: 22px;
    left: 115px;
}
.hot .hot_bottom .hot_box2 .hot_box2_1 h4,
.hot .hot_bottom .hot_box2 .hot_box2_2 h4,
.hot .hot_bottom .hot_box2 .hot_box2_3 h4,
.hot .hot_bottom .hot_box2 .hot_box2_4 h4,
.hot .hot_bottom .hot_box2 .hot_box2_5 h4,
.hot .hot_bottom .hot_box2 .hot_box2_6 h4 {
    position: absolute;
    width: 90px;
    height: 33px;
    top: 22px;
    left: 115px;
    font-size: 12px;
    color: #333333;
}
.hot_bottom .hot_box2 .hot_box2_2 {
    background: url(../images/images/images/hot_box2-2_03.png) no-repeat 18px 20px;
    border: 1px solid #ededed;
    border-top: 0;
    border-left: 0;
}
.hot_bottom .hot_box2 .hot_box2_3 {
    background: url(../images/images/images/hot_box2-4_03.png) no-repeat 10px 20px;
    border: 1px solid #ededed;
    border-top: 0;
    border-left: 0;
}
.hot_bottom .hot_box2 .hot_box2_4 {
    background: url(../images/images/images/hot_box2-4_03.png) no-repeat 10px 20px;
    border-right: 1px solid #ededed;
}
.hot_bottom .hot_box2 .hot_box2_5 {
    background: url(../images/images/images/hot_box2-4_03.png) no-repeat 10px 20px;
    border-right: 1px solid #ededed;
}
.hot_bottom .hot_box2 .hot_box2_6 {
    background: url(../images/images/images/hot_box2-6_03.png) no-repeat 10px 20px;
    border-right: 1px solid #ededed;
}
.hot_bottom .hot_box3 {
    float: left;
    width: 296px;
    height: 281px;
}
.hot_bottom .hot_box3 .hot_box3_1 {
    margin-top: 38px;
    width: 296px;
    height: 89px;
    background: url(../images/images/images/hot_box3-1-1_03.png) no-repeat 19px 18px;
}
.hot_bottom .hot_box3 .hot_box3_1 .user {
    width: 178px;
    height: 29px;
    line-height: 29px;
    margin-left: 118px;
    color: #333333;
}
.hot_bottom .hot_box3 .hot_box3_1 .user::before {
    float: left;
    width: 31px;
    height: 29px;
    margin-right: 7px;
    content: '';
    background: url(../images/images/images/hot_box3-1user_03.png);
}
.hot_bottom .hot_box3 .hot_box3_1 .content {
    width: 170px;
    height: 53px;
    margin: 7px 0 0 113px;
}
.hot_bottom .hot_box3 .hot_box3_1 .content .daimond {
    float: left;
    margin-top: 17px;
    border-top: 8px solid transparent;
    border-bottom: 8px solid transparent;
    border-right: 8px solid #f8f8f8;
}
.hot_bottom .hot_box3 .hot_box3_1 .content .content_words {
    float: right;
    width: 162px;
    height: 53px;
    padding: 10px 24px 7px 16px;
    background-color: #f8f8f8;
    color: #333333;
}
.hot_bottom .hot_box3 .hot_box3_2 {
    margin-top: 32px;
    width: 296px;
    height: 89px;
    background: url(../images/images/images/hot_box3_2_1_07.png) no-repeat 19px 18px;
}
.hot_bottom .hot_box3 .hot_box3_2 .user {
    width: 178px;
    height: 29px;
    line-height: 29px;
    margin-left: 118px;
    color: #333333;
}
.hot_bottom .hot_box3 .hot_box3_2 .user::before {
    float: left;
    width: 31px;
    height: 29px;
    margin-right: 7px;
    content: '';
    background: url(../images/images/images/hot_box3_2_2_07.png);
}
.hot_bottom .hot_box3 .hot_box3_2 .content {
    width: 170px;
    height: 53px;
    margin: 7px 0 0 113px;
}
.hot_bottom .hot_box3 .hot_box3_2 .content .daimond {
    float: left;
    margin-top: 17px;
    border-top: 8px solid transparent;
    border-bottom: 8px solid transparent;
    border-right: 8px solid #f8f8f8;
}
.hot_bottom .hot_box3 .hot_box3_2 .content .content_words {
    float: right;
    width: 162px;
    height: 53px;
    padding: 10px 24px 7px 16px;
    background-color: #f8f8f8;
    color: #333333;
}
    </style>
</head>

<body>
    <!-- 快捷導航欄 start -->
    <div class="shortcut">
        <div class="w">
            <div class="shortcutleft">
                <span>品优购欢迎您！</span>
                <span><a href="#">请登录</a></span>
                <span><a href="./register.html" class="red">免费注册</a></span>
            </div>
            <div class="shortcutright">
                <span><a href="#">我的订单</a></span>
                <span><a href="#">我的品优购&nbsp;</a></span>
                <span><a href="#">品优购会员</a></span>
                <span><a href="#">企业采购</a></span>
                <span><a href="#">关注品优购&nbsp;</a></span>
                <span><a href="#">客户服务&nbsp;</a></span>
                <span><a href="#" class="right">网站导航&nbsp;</a></span>
            </div>
        </div>
    </div>
    <!-- 快捷導航欄 end -->
    <!-- header start -->
    <header class="w header">
        <div class="logo">
            <h1>
                <a href="#" title="品優購">品優購</a>
            </h1>
        </div>
        <div class="search">
            <input type="search" placeholder="請輸入文字"><a href="#"><button>搜索</button></a>
            <ul class="hotwords">
                <li><a href="#" class="style_red">优惠购首发</a></li>
                <li><a href="#">亿元优惠</a></li>
                <li><a href="#">9.9元团购</a></li>
                <li><a href="#">美满99减30</a></li>
                <li><a href="#">办公用品</a></li>
                <li><a href="#">电脑</a></li>
                <li><a href="#">通信</a></li>
            </ul>
        </div>
        <div class="shopcar">
            <a href="#">我的购物车</a><span class="amount">8</span>
        </div>
    </header>
    <!-- header end -->
    <!-- 導航欄 start -->
    <nav class="w nav">
        <div class="dropdown">
            <div class="dt">商品詳細分類</div>
            <div class="dd">
                <ul>
                    <li><a href="#">家用電腦</a></li>
                    <li><a href="./list.html">手機、數碼、通信</a></li>
                    <li><a href="#">電腦、辦公</a></li>
                    <li><a href="#">家居、家具、家装、厨具</a></li>
                    <li><a href="#">男装、女装、童装、内衣</a></li>
                    <li><a href="#">个户化妆、清洁用品、宠物</a></li>
                    <li><a href="#">鞋靴、箱包、珠宝、奢侈品</a></li>
                    <li><a href="#">运动户外、钟表</a></li>
                    <li><a href="#">汽车、汽车用品</a></li>
                    <li><a href="#">母婴、玩具乐器</a></li>
                    <li><a href="#">食品、酒类、生鲜、特产</a></li>
                    <li><a href="#">医药保健</a></li>
                    <li><a href="#">图书、音像、电子书</a></li>
                    <li><a href="#">彩票、旅行、充值、票务</a></li>
                    <li><a href="#">理财、众筹、白条、保险</a></li>
                </ul>
            </div>
        </div>
        <ul class="nav_box">
            <li><a href="#" class="left">服裝城</a></li>
            <li><a href="#">女裝館</a></li>
            <li><a href="#">傳智超市</a></li>
            <li><a href="#">全球購</a></li>
            <li><a href="#">閃購</a></li>
            <li><a href="#">團購</a></li>
            <li><a href="#">排賣</a></li>
            <li><a href="#">有趣</a></li>
        </ul>
    </nav>
    <!-- 導航欄 end -->
    <!-- banner、aside start-->
    <div class="w main">
        <div class="banner">
            <img src="images/images/banner.png" alt="">
        </div>
        <div class="aside">
            <div class="aside_news">
                <h4>品优购快报</h4>
                <ul>
                    <li><a href="#"><span>[特惠]</span>備戰開學季 全民半價購數碼</a></li>
                    <li><a href="#"><span>[公告]</span>品優穩佔家家電網購六成份額</a></li>
                    <li><a href="#"><span>[特惠]</span>百元中秋全品類禮券限量額</a></li>
                    <li><a href="#"><span>[公告]</span>尚品優生鮮 想陽澄湖大閘蟹</a></li>
                    <li><a href="#"><span>[特惠]</span>每日享折扣品優品質游</a></li>
                </ul>
            </div>
            <div class="aside_class">
                <div class="minus"></div>
                <ul>
                    <li><a href="#"><i class="pic1"></i>話費</a></li>
                    <li><a href="#"><i class="pic2"></i>機票</a></li>
                    <li><a href="#"><i class="pic3"></i>電影票</a></li>
                    <li><a href="#"><i class="pic4"></i>遊戲</a></li>
                    <li><a href="#"><i class="pic5"></i>彩票</a></li>
                    <li><a href="#"><i class="pic6"></i>加油卡</a></li>
                    <li><a href="#"><i class="pic7"></i>酒店</a></li>
                    <li><a href="#"><i class="pic8"></i>火車票</a></li>
                    <li><a href="#"><i class="pic9"></i>重酬</a></li>
                    <li><a href="#"><i class="pic10"></i>理財</a></li>
                    <li><a href="#"><i class="pic11"></i>禮品卡</a></li>
                    <li><a href="#"><i class="pic12"></i>白條</a></li>
                </ul>
            </div>
            <div class="aside_bg">
                <a href="#"></a>
            </div>
        </div>
    </div>
    <!-- banner、asied end-->
    <!-- items_box start -->
    <aside class="floor">
        <ul>
            <li><a href="#machine">家用电器</a></li>
            <li><a href="#cellphone">手機通讯</a></li>
            <li><a href="#computer">电脑办公</a></li>
            <li><a href="#">家居家具</a></li>
            <li><a href="#">生活用品</a></li>
            <li><a href="#">运动户外</a></li>
            <li><a href="#">汽车用品</a></li>
            <li><a href="#">食品酒类</a></li>
            <li><a href="#">医药保健</a></li>
            <li><a href="#">图书音像</a></li>
            <li><a href="#">金融彩票</a></li>
        </ul>
    </aside>
    <!-- items_box end -->
    <!-- 今日推薦 start -->
    <section class="w suggest">
        <dl>
            <dt>
                <p></p>
                <p>今日推薦</p>
            </dt>
            <dd class="goods1">
                <a href="#">
                    <div class="lf">
                        <h4>优质好货</h4>
                        <p>滿300減100</p>
                        <p>满500减200</p>
                    </div>
                    <div class="rf"></div>
                </a>
            </dd>
            <li></li>
            <dd class="goods2">
                <a href="#">
                    <div class="lf">
                        <h4>品牌尾貨</h4>
                        <p>滿300減100</p>
                        <p>團購低至9.9</p>
                        <div>團購</div>
                    </div>
                    <div class="rf"></div>
                </a>
            </dd>
            <li></li>
            <dd class="goods3">
                <a href="#">
                    <div class="lf">
                        <h4>時尚穿搭</h4>
                        <p>低至3.6折</p>
                        <p>暑期出遊季</p>
                        <div>閃購</div>
                    </div>
                    <div class="rf"></div>
                </a>
            </dd>
            <li></li>
            <dd class="goods4">
                <a href="#">
                    <div class="lf">
                        <h4>0點上新</h4>
                        <p>全場包郵</p>
                        <p>低至1折</p>
                        <div>閃購</div>
                    </div>
                    <div class="rf"></div>
                </a>
            </dd>
        </dl>
    </section>
    <!-- 今日推薦 end -->
    <!-- 猜你喜歡的 start -->
    <section class="w guesslike">
        <div class="guess_top">
            <span>猜你喜歡的</span>
            <span class="change_round"><a href="#">換一批</a></span>
        </div>
        <div class="guess_bottom">
            <ul>
                <li class="guess_goods1">
                    <a href="#">
                        <div></div>
                        <div>
                            <h4>阳光美包新款单肩包女包时尚子母包四件套女</h4>
                            <span>¥116.00</span>
                        </div>
                    </a>
                </li>
                <li class="guess_goods2">
                    <a href="#">
                        <div></div>
                        <div>
                            <h4>爱仕达 30CM炒锅不粘锅NWG8330E电磁炉炒</h4>
                            <span>¥99.00</span>
                        </div>
                    </a>
                </li>
                <li class="guess_goods3">
                    <a href="#">
                        <div></div>
                        <div>
                            <h4>捷波朗<br />（jabra）BOOSI劲步</h4>
                            <span>¥245.00</span>
                        </div>
                    </a>
                </li>
                <li class="guess_goods4">
                    <a href="#">
                        <div></div>
                        <div>
                            <h4>欧普<br />JYLZ08面板灯平板灯铝</h4>
                            <span>¥238.00</span>
                        </div>
                    </a>
                </li>
                <li class="guess_goods5">
                    <a href="#">
                        <div></div>
                        <div>
                            <h4>三星<br />（G5500）移动联</h4>
                            <span>¥649.00</span>
                        </div>
                    </a>
                </li>
                <li class="guess_goods6">
                    <a href="#">
                        <div></div>
                        <div>
                            <h4>韩国所望<br />紧致湿润精华露400ml</h4>
                            <span>¥649.00</span>
                        </div>
                    </a>
                </li>
            </ul>
        </div>
    </section>
    <!-- 猜你喜歡的 end  -->
    <!-- 有趣區 start -->
    <section class="w fun">
        <div class="fun_top">传智播客．有趣区</div>
        <div class="fun_bottom">
            <div class="fun_box1">
                <a href="#">
                    <h4>传智播客好书榜<br />
                        <p>畅销推荐低至一折</p>
                    </h4>
                </a>
            </div>
            <div class="fun_box2">
                <div class="title">好東西</div>
                <div class="content_1">
                    <a href="#">
                        <h4>達人推薦</h4>
                        <p>雷神金属机械键盘<br /><span>与你相见恨晚</span></p>
                    </a>
                </div>
                <div class="content_2">
                    <a href="">
                        <h4>發現好物</h4>
                        <p>一不小心霸氣外露<br /><span>等你來</span></p>
                    </a>
                </div>
            </div>
            <div class="fun_box3">
                <div class="title">品牌街</div>
                <div class="content_3">
                    <a href="#">
                        <h4>苏泊尔</h4>
                        <p>返场大秀场<br /><span>爆品直降100元</span></p>
                    </a>
                </div>
                <div class="content_4">
                    <a href="">
                        <h4>國際大牌</h4>
                        <p>adidas<br /><span>部分3免1</span></p>
                    </a>
                </div>
                <div class="content_5">
                    <a href="">
                        <h4>本週特賣</h4>
                        <p>大牌折扣<br /><span>每週上新</span></p>
                    </a>
                </div>
            </div>
            <div class="fun_box4">
                <ul>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                </ul>
            </div>
        </div>
    </section>
    <!-- 有趣區 end -->
    <!-- 家用電器  start-->
    <section class=" w machine">
        <div class="machine_top">
            <span id="machine">家用電器</span>
            <ul>
                <li><a href="#">高端电器</a></li>
                <li></li>
                <li><a href="#">新奇特</a></li>
                <li></li>
                <li><a href="#">空气/净水</a></li>
                <li></li>
                <li><a href="#">应季电器</a></li>
                <li></li>
                <li><a href="#">个护健康</a></li>
                <li></li>
                <li><a href="#">厨房电器</a></li>
                <li></li>
                <li><a href="#">生活电器</a></li>
                <li></li>
                <li><a href="#">大家电</a></li>
                <li></li>
                <li><a href="#" class="style_red">热门</a></li>
            </ul>
        </div>
        <div class="machine_bottom">
            <div class="machine_box1">
                <div class="machine_items">
                    <ul>
                        <li><a href="#">節能補貼</a></li>
                        <li><a href="#">4K電視</a></li>
                        <li><a href="#">空氣淨化器</a></li>
                        <li><a href="#">IH電飯褒</a></li>
                        <li><a href="#">滾筒洗衣機</a></li>
                        <li><a href="#">電熱水器</a></li>
                    </ul>
                </div>
                <div class="machine_pic1">
                    <a href="#">
                        <h4>三星曲面電視
                            <p>
                                抽獎送好禮
                            </p>
                        </h4>
                    </a>
                </div>
            </div>
            <div class="machine_box2">
                <a href="#">
                    <h4>燒水壺智能光控泡茶壺茶具裝
                        <p>
                            滿299.00減40.00
                        </p>
                    </h4>
                </a>
                <li></li>
                <li></li>
                <li></li>
            </div>
            <div class="machine_box3">
                <div class="box3_1">
                    <a href="#">
                        <h4>每滿200減20元
                            <p>烘培節1元搶購</p>
                        </h4>
                    </a>
                </div>
                <div class="box3_2">
                    <a href="#">
                        <h4>買樂視電視想巨惠
                            <p>送60個月會員</p>
                        </h4>
                    </a>
                </div>
            </div>
            <div class="machine_box4">
                <a href="#">
                    <h4>8.20彩電宅購節
                        <p>65寸4K智能電視3799</p>
                    </h4>
                </a>
            </div>
            <div class="machine_box5">
                <div class="box5_1">
                    <a href="#">
                        <h4>消暑神器全場領券
                            <p>1元贏空調</p>
                        </h4>
                    </a>
                </div>
                <div class="box5_2">
                    <a href="#">
                        <h4>買樂視電視想巨惠
                            <p>送60個月會員</p>
                        </h4>
                    </a>
                </div>
            </div>
        </div>
    </section>
    <!-- 家用電器 end-->
    <!-- machine brand start -->
    <section class="w machine_brand">
        <ul>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
        </ul>
    </section>
    <!-- machine brand end -->
    <!-- 手機通訊 start -->
    <section class=" w cellphone">
        <div class="cellphone_top">
            <span id="cellphone">手機通訊</span>
            <ul>
                <li><a href="#">手機配件</a></li>
                <li></li>
                <li><a href="#">店舖精選</a></li>
                <li></li>
                <li><a href="#">手機卡</a></li>
                <li></li>
                <li><a href="#">合約機</a></li>
                <li></li>
                <li><a href="#">口碑推薦</a></li>
                <li></li>
                <li><a href="#">高性價比</a></li>
                <li></li>
                <li><a href="#">新機嚐鮮</a></li>
                <li></li>
                <li><a href="#">品質優選</a></li>
                <li></li>
                <li><a href="#">热门</a></li>
            </ul>
        </div>
        <div class="cellphone_bottom">
            <div class="cellphone_box1">
                <div class="cellphone_items">
                    <ul>
                        <li><a href="#" style="margin:0;">測試測試</a></li>
                        <li><a href="#">手機通訊</a></li>
                        <li><a href="#">雙卡雙待</a></li>
                        <li><a href="#">自營配件</a></li>
                        <li><a href="#">金屬機身</a></li>
                        <li><a href="#">高清螢幕</a></li>
                    </ul>
                </div>
                <div class="cellphone_pic1">
                    <a href="#">
                        <h4>中興A1 低至499元
                            <p>
                                國民指紋，超6萬好評
                            </p>
                        </h4>
                    </a>
                </div>
            </div>
            <div class="cellphone_box2">
                <a href="#">
                    <h4>360 N4S限量版
                        <p>
                            1199元搶購
                        </p>
                    </h4>
                </a>
                <li></li>
                <li></li>
                <li></li>
            </div>
            <div class="cellphone_box3">
                <div class="box3_1">
                    <a href="#">
                        <h4>Moto X級
                            <p>低至¥2999</p>
                        </h4>
                    </a>
                </div>
                <div class="box3_2">
                    <a href="#">
                        <h4>樂max2 限量秒殺
                            <p>每日1899秒</p>
                        </h4>
                    </a>
                </div>
            </div>
            <div class="cellphone_box4">
                <a href="#">
                    <h4>G9青春版玫瑰金首發
                        <p>贏0元試用</p>
                    </h4>
                </a>
            </div>
            <div class="cellphone_box5">
                <div class="box5_1">
                    <a href="#">
                        <h4>榮耀V8 2K屏
                            <p>¥2779元</p>
                        </h4>
                    </a>
                </div>
                <div class="box5_2">
                    <a href="#">
                        <h4>vivo x7星空灰
                            <p>1元迎新機</p>
                        </h4>
                    </a>
                </div>
            </div>
        </div>
    </section>
    <!-- 手機通訊 end -->
    <!-- cellphone brand start -->
    <section class="w cellphone_brand">
        <ul>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
        </ul>
    </section>
    <!-- cellphone brand end -->
    <!-- computer start -->
    <section class=" w computer">
        <div class="computer_top">
            <span id="computer">電腦辦公</span>
            <ul>
                <li><a href="#">精選配件</a></li>
                <li></li>
                <li><a href="#">文具電教</a></li>
                <li></li>
                <li><a href="#">辦公/網路</a></li>
                <li></li>
                <li><a href="#">電競遊戲</a></li>
                <li></li>
                <li><a href="#">DIY硬件</a></li>
                <li></li>
                <li><a href="#">智能/外設</a></li>
                <li></li>
                <li><a href="#">潮流影音</a></li>
                <li></li>
                <li><a href="#">電腦/平板</a></li>
                <li></li>
                <li><a href="#">热门</a></li>
            </ul>
        </div>
        <div class="computer_bottom">
            <div class="computer_box1">
                <div class="computer_items">
                    <ul>
                        <li><a href="#">SSD硬盤</a></li>
                        <li><a href="#">顯示器</a></li>
                        <li><a href="#">機械鍵盤</a></li>
                        <li><a href="#">台式機</a></li>
                        <li><a href="#">組裝電腦</a></li>
                        <li><a href="#">配件專區</a></li>
                    </ul>
                </div>
                <div class="computer_pic1">
                    <a href="#">
                        <h4>電腦特惠直降3000
                            <p>
                                遊戲本期六免息
                            </p>
                        </h4>
                    </a>
                </div>
            </div>
            <div class="computer_box2">
                <a href="#">
                    <h4>大牌相機低價搶
                        <p>
                            運動相機低至¥299
                        </p>
                    </h4>
                </a>
                <li></li>
                <li></li>
                <li></li>
            </div>
            <div class="computer_box3">
                <div class="box3_1">
                    <a href="#">
                        <h4>平板新世界
                            <p>開啟2IN1時代</p>
                        </h4>
                    </a>
                </div>
                <div class="box3_2">
                    <a href="#">
                        <h4>低價來襲
                            <p>機械鍵盤低至99元</p>
                        </h4>
                    </a>
                </div>
            </div>
            <div class="computer_box4">
                <a href="#">
                    <h4>全場6期分期免習
                        <p>我和DIY有個約會</p>
                    </h4>
                </a>
            </div>

            <div class="computer_box5">
                <div class="box5_1">
                    <a href="#">
                        <h4>消暑神器全場領券
                            <p>1元贏空調</p>
                        </h4>
                    </a>
                </div>
                <div class="box5_2">
                    <a href="#">
                        <h4>潮流手配 尖叫來襲
                            <p>滿99元減30元</p>
                        </h4>
                    </a>
                </div>
            </div>
        </div>
    </section>
    <!-- computer end -->
    <!-- computer brand start -->
    <section class="w computer_brand">
        <ul>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
        </ul>
    </section>
    <!-- computer brand end -->
    <!-- 熱門瘋搶 start-->
    <section class="w hot">
        <div class="hot_top">
            熱門瘋搶
        </div>
        <div class="hot_bottom">
            <div class="hot_box1">
                <h4>暴風魔境 小D虛擬現實智能VR眼鏡3
                    <p>¥79.00</p>
                </h4>
            </div>
            <div class="hot_box2">
                <div class="hot_box2_1">
                    <h4>宇博7800毫 Z3 移動電源充電
                        <p>¥79.00</p>
                    </h4>
                </div>
                <div class="hot_box2_2">
                    <h4>全微 (transwin) A-920 2.0聲道
                        <p>¥29.00</p>
                    </h4>
                </div>
                <div class="hot_box2_3">
                    <h4>2016夏季新款短袖簍空大V領蕾絲
                        <p>¥129.00</p>
                    </h4>
                </div>
                <div class="hot_box2_4">
                    <h4>2016夏季新款短袖簍空大V領蕾絲
                        <p>¥128.00</p>
                    </h4>
                </div>
                <div class="hot_box2_5">
                    <h4>2016夏季新款短袖簍空大V領蕾絲
                        <p>¥129.00</p>
                    </h4>
                </div>
                <div class="hot_box2_6">
                    <h4>璞衣 2016邱東西新款復古棉麻印花
                        <p>¥129.00</p>
                    </h4>
                </div>
            </div>
            <div class="hot_box3">
                <div class="hot_box3_1">
                    <div class="user">
                        0807**
                    </div>
                    <div class="content">
                        <div class="daimond"></div>
                        <div class="content_words">
                            高分辨率的頻幕用著和台式機一樣.......
                        </div>
                    </div>
                </div>
                <div class="hot_box3_2">
                    <div class="user">
                        0807**
                    </div>
                    <div class="content">
                        <div class="daimond"></div>
                        <div class="content_words">
                            高分辨率的頻幕用著和台式機一樣.......
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>
    <!-- 熱門瘋搶 end -->
    <!-- footer start-->
    <footer class="footer">
        <!-- 服務 -->
        <div class="w mod_service ">
            <ul>
                <li>
                    <div class="pic_sprite1"></div>
                    <span>
                        <h4>正品保障</h4>正品保障，提供發票
                    </span>
                </li>
                <li>
                    <div class="pic_sprite2"></div>
                    <span>
                        <h4>極速物流</h4>極速物流，極速運送
                    </span>
                </li>
                <li>
                    <div class="pic_sprite3"></div>
                    <span>
                        <h4>無憂售後</h4>7天无理由退换货
                    </span>
                </li>
                <li>
                    <div class="pic_sprite4"></div>
                    <span>
                        <h4>特色服務</h4>私人定制家电套餐
                    </span>
                </li>
                <li>
                    <div class="pic_sprite5"></div>
                    <span>
                        <h4>幫助中心</h4>您的購物指南
                    </span>
                </li>
            </ul>
        </div>
        <!-- 幫助 -->
        <div class="w mod_help">
            <dl>
                <dt>購物指南
                <dd><a href="#">購物流程</a></dd>
                <dd><a href="#">會員介紹</a></dd>
                <dd><a href="#">生活旅行/團購</a></dd>
                <dd><a href="#">常見問題</a></dd>
                <dd><a href="#">大家電</a></dd>
                <dd><a href="#">聯繫客服</a></dd>
                </dt>
            </dl>
            <dl>
                <dt>配送方式
                <dd><a href="#">上禮自提</a></dd>
                <dd><a href="#">211限時送</a></dd>
                <dd><a href="#">配送服務查詢</a></dd>
                <dd><a href="#">配送收費取標準</a></dd>
                <dd><a href="#">海外配送</a></dd>
                </dt>
            </dl>
            <dl>
                <dt>支付方式
                <dd><a href="#">購貨到付款</a></dd>
                <dd><a href="#">到線支付</a></dd>
                <dd><a href="#">分期付款</a></dd>
                <dd><a href="#">郵局匯款</a></dd>
                <dd><a href="#">公司轉帳</a></dd>
                </dt>
            </dl>
            <dl>
                <dt>售後服務
                <dd><a href="#">售後政策</a></dd>
                <dd><a href="#">價格辯護</a></dd>
                <dd><a href="#">退款說明</a></dd>
                <dd><a href="#">返修/退換貨</a></dd>
                <dd><a href="#">取消訂單</a></dd>
                </dt>
            </dl>
            <dl>
                <dt>特色服務
                <dd><a href="#">奪寶島</a></dd>
                <dd><a href="#">會DIY裝機</a></dd>
                <dd><a href="#">延保服務</a></dd>
                <dd><a href="#">品優購E卡</a></dd>
                <dd><a href="#">品優購通信</a></dd>
                </dt>
            </dl>
            <div>
                <h4>幫助中心</h4>
                <img src="./images/images/qrcode_07.jpg">
                品優購客戶端
            </div>
        </div>
        <!-- 關於我們 -->
        <div class="w mod_copyright">
            <ul>
                <li><a href="#">关于我们</a></li>
                <li><a href="#">联系我们</a></li>
                <li><a href="#">联系客服</a></li>
                <li><a href="#">商家入驻</a></li>
                <li><a href="#">营销中心</a></li>
                <li><a href="#">手机品优购</a></li>
                <li><a href="#">友情链接</a></li>
                <li><a href="#">销售联盟</a></li>
                <li><a href="#">品优购社区</a></li>
                <li><a href="#">品优购公益</a></li>
                <li><a href="#">English Site</a></li>
                <li><a href="#">Contact U</a></li>
            </ul><br />
            <div>地址：北京市昌平区建材城西路金燕龙办公楼一层 邮编：100096 电话：400-618-4000 传真：010-82935100 邮箱: zhanghj+itcast.cn</div>
            <div>京ICP备08001421号京公网安备110108007702</div>
        </div>
    </footer>
    <!-- footer end-->
</body>

</html>
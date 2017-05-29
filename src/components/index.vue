<template>
  <div>
    <header>
      <div class="header_box">
        <div class="sas_box">
          <a>
            <img src='../img/scan.png'>
          </a>
          <span>{{act}}</span>
        </div>
        <div class="input_box">
          <input type="text">
        </div>
        <div class="xx_box">
          <a>
            <img src='../img/message.png'>
          </a>
          <span>{{mess}}</span>
        </div>
      </div>
      <div class="lb_box">
        <ul>
          <li>
            <a>
              <img src='../img/header_1.jpg'>
            </a>
          </li>
          <li>
            <a>
              <img src='../img/header_2.jpg'>
            </a>
          </li>
          <li>
            <a>
              <img src='../img/header_3.jpg'>
            </a>
          </li>
          <li>
            <a>
              <img src='../img/header_4.jpg'>
            </a>
          </li>
          <div style="clear: both"></div> <!--清除浮动使ul标签高度被li撑开-->
        </ul>
        <ul>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </div>
    </header>
    <nav>
      <div class="dh_box">
        <ul>
          <li><a><img src='../img/nav_1.png'></a><p>京东超市</p></li>
          <li><a><img src='../img/nav_2.png'></a><p>全球购</p></li>
          <li><a><img src='../img/nav_3.png'></a><p>服装城</p></li>
          <li><a><img src='../img/nav_4.png'></a><p>京东生鲜</p></li>
          <li><a><img src='../img/nav_5.png'></a><p>京东到家</p></li>
        </ul>
        <ul>
          <li><a><img src='../img/nav_6.png'></a><p>充值缴费</p></li>
          <li><a><img src='../img/nav_7.png'></a><p>领京豆</p></li>
          <li><a><img src='../img/nav_8.png'></a><p>领券</p></li>
          <li><a><img src='../img/nav_9.png'></a><p>惠赚钱</p></li>
          <li><a><img src='../img/nav_10.png'></a><p>全部</p></li>
        </ul>
      </div>
    </nav>.
    <main>
      <!--<span>京东秒杀</span>-->
      <!--<span>16点场</span>-->

    </main>
    <footer>

    </footer>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  data () {
    return {
      act: '扫啊扫',
      mess: '消息'
    }
  }

}
</script>
<style>
  header{
    width: 100%;
  }
  .header_box{
    width: 100%;
    position: fixed;
    z-index: 1000;
  }
  .sas_box{
    width: 50px;
    height: 50px;
    position: absolute;
    left: 0;
    top: 0;
  }
  .xx_box{
    width: 50px;
    height: 50px;
    position: absolute;
    right: 0;
    top: 0;
  }
  .sas_box > a ,.xx_box > a {
    width: 30px;
    height: 30px;
    display: block;
    position: relative;
    left: 10px;
    top: 5px;
  }
  .sas_box > a > img,.xx_box > a > img{
    width: 30px;
    height: 30px;
  }
  .input_box{
    width: 100%;
    padding-left: 50px;
    padding-right: 50px;
    box-sizing: border-box;
  }

  .input_box > input{
    width: 100%;
    height: 50px;
    border-radius: 25px;
    border:1px solid red;
    -webkit-tap-highlight-color: transparent;
    outline-color: transparent;
  }
  header .header_box div span{
    font-size: 12px;
    text-align: center;
    display: block;
    width: 100%;
    position: relative;
    top: 5px;;
    color: #ffffff;
  }
  .lb_box{
    width: 100%;
    overflow: hidden;
    z-index: 500;
    position: relative;
  }
  .lb_box > ul {
    width: 1000%;
  }
  .lb_box > ul > li{
    width: 10%;
    float: left;
  }
  .lb_box > ul > li > a{
    width: 100%;
    display: block;
  }
  .lb_box > ul > li > a > img{
    width: 100%;
    vertical-align: middle;
  }
  .lb_box > ul:nth-child(2){
    width: 120px;
    height: 10px;
    position: absolute;
    left: 50%;
    bottom: 10px;
    margin-left: -60px;
  }
  .lb_box > ul:nth-child(2) li{
    width: 6px;
    height: 6px;
    border-radius: 3px;
    border: 1px solid black;
    margin-left: 32px;
    box-sizing: border-box;
  }
  .lb_box > ul:nth-child(2) li:nth-child(1){
    background-color: #ffffff;
  }
  .lb_box > ul:nth-child(2) li:first-child{
    margin-left: 0px;
  }
  nav{
    width: 100%;
    background-color: bisque;
  }
  .dh_box{
    width: 100%;
  }
  .dh_box  ul {
    width: 100%;
    display: flex;
  }
  .dh_box  ul li{
    flex:1;
    text-align: center;
    margin-top: 10px;
  }
  .dh_box  ul:last-child{
    padding-bottom: 10px;
  }
  .dh_box ul li a{
    width: 100%;
    display: block;
  }
  .dh_box ul li a img {
    width: 40px;
    height: 40px;
  }
  .dh_box ul li  > p{
    margin-top: 4px;
  }
</style>


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
<style lang="less" rel="stylesheet/less" type="text/less">
  @import "../less/app.less";
</style>


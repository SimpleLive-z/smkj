<template>
<div>
  <div class="footerPc">
    <div class="suggest">
      <form action="" method="post">
        <label for="suggests">留下您的意见和建议：</label>
        <input type="text" name="suggest" id="suggests" value="">
        <input type="submit">
      </form>
    </div>

    <div class="contact">
      <div class="phone info">
        <a href=""> <img src="../../../static/img/icon_phone.png" class="foot_icon" alt=""></a>
        <div class="foot_details">
          <p>电话</p>
          <p>13123567359</p>
        </div>
      </div>
      <div class="chuanz info">
        <a href=""><img src="../../../static/img/icon_chuanz.png" class="foot_icon" alt=""></a>
        <div class="foot_details">
          <p>传真</p>
          <p>028-3367357</p>
        </div>
      </div>
      <div class="qq info">
        <a href=""> <img src="../../../static/img/icon_qq.png" class="foot_icon" alt=""></a>
        <div class="foot_details">
          <p>QQ</p>
          <p>121342190</p>
        </div>
      </div>
      <div class="email info">
        <a href=""> <img src="../../../static/img/icon_email.png" class="foot_icon" alt=""></a>
        <div class="foot_details">
          <p>邮箱</p>
          <p>121342190@qq.com</p>
        </div>
      </div>
      <div class="address info">
        <a href=""> <img src="../../../static/img/icon_address.png" class="foot_icon" alt=""></a>
        <div class="foot_details">
          <p>地址</p>
          <p>成都市锦江区东大街芷泉街229号</p>
        </div>
      </div>
    </div>
    <hr />
    <div class="footLink clearfix">
      <div class="leftLink pull-left">
        <div class="oprations">
          <h4>业务体系</h4>
          <ul>
            <li><a href="">网页设计</a></li>
            <li><a href="">UI设计</a></li>
            <li><a href="">平面设计</a></li>
            <li><a href="">网站建设</a></li>
            <li><a href="">购物商城</a></li>
            <li><a href="">微信开发</a></li>
          </ul>
        </div>
        <div class="aboutWe">
          <h4>关于我们</h4>
          <ul>
            <li><a href="">关于我们</a></li>
            <li><a href="">加入我们</a></li>
            <li><a href="">联系我们</a></li>
          </ul>
        </div>
      </div>
      <div class="codes pull-right">
        <div class="codeLeft">
          <img src="../../../static/img/code_03.png" alt="">
          <p>商脉微信公众号</p>
        </div>
        <div class="codeRight">
          <img src="../../../static/img/code_05.png" alt="">
          <p>商脉官方微博</p>
        </div>
      </div>
    </div>

    <p class="banq">版权归成都商脉科技有限公司所有</p>
  </div>
</div>
</template>

<script>
export default {
  name: "FooterBottom"
}
</script>

<style scoped>
@import "../../../static/css/footerBottom.css";
</style>

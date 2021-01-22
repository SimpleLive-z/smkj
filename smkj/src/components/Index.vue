<template>
  <div>
    <Public>
      <!-- 广告栏   -->
      <div slot="banner" class="banner container-fluid">
        <div id="bannerCarousel" class="carousel slide" data-ride="carousel" data-interval="2000">
          <ol class="carousel-indicators">
            <li data-target="#bannerCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#bannerCarousel" data-slide-to="1"></li>
            <li data-target="#bannerCarousel" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">
            <div class="item active">
              <img src="../../static/img/banner_02.png" alt="">
            </div>
            <div class="item">
              <img src="../../static/img/banner_02.png" alt="">
            </div>
            <div class="item">
              <img src="../../static/img/banner_02.png" alt="">
            </div>
          </div>
          <a class="left carousel-control" href="#bannerCarousel" role="button" data-slide="prev">
            <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="right carousel-control" href="#bannerCarousel" role="button" data-slide="next">
            <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
      <!--关于公司pc-->
      <div slot="slot1" class="firmPc">
        <div class="firmContent">
          <div class="firmPcLeft">
            <div class="detail">
              <h3>关于商脉</h3>
              <div class="subtitle">
                <h6>优秀的产品是优雅设计与精湛技术的完美结合</h6>
              </div>
              <div class="substance">
                <p>
                  自成立以来，始终致力于为中国企业特别是成长型企业提供专业信息化服务，在川内率先开创了专属个性化定制模式，实现企业“信息化运营”。商脉科技已成功为川内多家知名企业客户提供了全方位、多层面的信息化解决方案。
                </p>
                <p> 公司服务涵盖了网站品牌策划、网络品牌优化与推广、网页创意设计、官方电子商城、微信营销平台、技术方案实施等。</p>
              </div>
            </div>
            <div class="more"><a href=""><img src="../../static/img/more_03.png" alt=""></a></div>
          </div>
          <div class="firmPcRight">
            <div class="detail pull-right clearfix">
              <h5>成都商脉科技有限公司</h5>
              <p>四川商脉科技有限公司，位于成都市锦江区大型商圈内，注册资金一千万（人民币），资金实力雄厚，并拥有行业顶级的自主研发设计技术人才。</p>

            </div>
            <div class="pic">
              <img src="../../static/img/pic1_03.png" alt="">
            </div>
          </div>
        </div>
      </div>
      <!--业务体系-->
      <div class="service" slot="slot2">
        <div class="serviceContent">
          <div class="opration">
            <div class="subtitle">
              <h3>业务体系</h3>
              <h6>商脉专注于企业网络品牌规划打造同一网站不同终端的统一视觉形象</h6>
            </div>
            <div class="oprationInfo">
              <div class="o-link">
                <div class="icon i-active"><a href=""><img src="../../static/img/icon1.png" alt=""></a></div>
                <p>网页设计</p>
              </div>
              <div class="o-link">
                <div class="icon"><a href=""><img src="../../static/img/icon2_03.png" alt=""></a></div>
                <p>UI设计</p>
              </div>
              <div class="o-link">
                <div class="icon i-active"><a href=""><img src="../../static/img/icon3.png" alt=""></a></div>
                <p>平面</p>
              </div>
              <div class="o-link">
                <div class="icon"><a href=""><img src="../../static/img/icon4.png" alt=""></a></div>
                <p>网页设计</p>
              </div>
              <div class="o-link">
                <div class="icon"><a href=""><img src="../../static/img/icon5.png" alt=""></a></div>
                <p>UI设计</p>
              </div>
              <div class="o-link">
                <div class="icon"><a href=""><img src="../../static/img/icon6.png" alt=""></a></div>
                <p>平面</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!--优秀作品-->
      <div class="worksPc" slot="slot3">
        <div class="title">
          <h3>优秀作品</h3>
          <div class="subtitle">
            <h6>我们足够优秀，每一次优秀都来源于每一个好的case</h6>
          </div>
        </div>
        <div class="workContentPc">
          <ul>
            <li><a href="">ALL</a></li>
            <li><a href="">网页设计</a></li>
            <li><a href="">UI设计</a></li>
            <li><a href="" class="workLink">平面设计</a></li>
            <li><a href="" class="workMore"><img src="../../static/img/i-more_03.png" alt="">MORE</a>
            </li>
          </ul>
          <div class="workDetail">
            <div class="work w-active">
              <img src="../../static/img/wpic1_03.png" alt="">
              <p>林氏木业·家居品牌营销网站</p>
            </div>
            <div class="work">
              <img src="../../static/img/wpic1_03.png" alt="">
              <p>林氏木业·家居品牌营销网站</p>
            </div>
            <div class="work">
              <img src="../../static/img/wpic1_03.png" alt="">
              <p>林氏木业·家居品牌营销网站</p>
            </div>
          </div>
        </div>
      </div>
      <!--人才共享-->
      <div class="personnel" slot="slot4">
        <div class="personPc">
          <div class="title">
            <h3>人才共享</h3>
            <div class="subtitle">
              <h6>力求团队思想与目标一致，让工作的每一分钟都有效率</h6>
            </div>
          </div>
          <div class="pList">
            <div class="pInfo">
              <a href=""><img src="../../static/img/pic2_03.png" alt="" srcset=""></a>
              <p>UI设计师</p>
            </div>
            <div class="pInfo pAction">
              <a href=""><img src="../../static/img/pic2_03.png" alt="" srcset=""></a>
              <p>UI设计师</p>
            </div>
            <div class="pInfo">
              <a href=""><img src="../../static/img/pic2_03.png" alt="" srcset=""></a>
              <p>UI设计师</p>
            </div>
          </div>
          <ul>
            <li class="active"></li>
            <li></li>
            <li></li>
          </ul>
        </div>
      </div>
      <!--新闻动态-->
      <div class="newsPc" slot="slot5">
        <div class="title pull-right clearfix">
          <h3>新闻动态</h3>
          <div class="subtitle">
            <h6>我们足够优秀，每一次优秀都来源于每一个好的case</h6>
          </div>
        </div>
        <div class="newsNav">
          <ul>
            <li><a href="" class="newLink">ALL</a></li>
            <li><a href="">公司动态</a></li>
            <li><a href="">行业动态</a></li>
            <li class="more"><a href="" class="moreNew"><img src="../../static/img/i-more_03.png" alt="">MROE</a>
            </li>
          </ul>
        </div>
        <div class="newsInfo">
          <div class="newInfo">
            <div class="newContent">
              <a href=""><img src="../../static/img/pic3_03.png" alt=""></a>
              <p>2017年你该如何规划 </p>
              <p> 经过上半年的市场观察，成都商脉科技有限......</p>
            </div>
            <div class="morenews pull-right clearfix">
              <img src="../../static/img/more_03.png" alt="">
            </div>
          </div>
          <div class="newInfo">
            <div class="newContent">
              <a href=""><img src="../../static/img/pic3_03.png" alt=""></a>
              <p>2017年你该如何规划 </p>
              <p> 经过上半年的市场观察，成都商脉科技有限......</p>
            </div>
            <div class="morenews pull-right clearfix">
              <img src="../../static/img/more_03.png" alt="">
            </div>
          </div>
          <div class="newInfo">
            <div class="newContent">
              <a href=""><img src="../../static/img/pic3_03.png" alt=""></a>
              <p>2017年你该如何规划 </p>
              <p> 经过上半年的市场观察，成都商脉科技有限......</p>
            </div>
            <div class="morenews pull-right clearfix">
              <img src="../../static/img/more_03.png" alt="">
            </div>
          </div>
        </div>
      </div>
    </Public>
  </div>
</template>

<script>
import Public from "./common/Public";
// import HeaderTop from "./common/HeaderTop";
// import FooterBottom from "./common/FooterBottom";
// import Aside from "./common/Aside";

export default {
  name: "Index",
  components: {
    Public
    // HeaderTop,
    // FooterBottom,
    // Aside
  }
}
</script>

<style scoped>
@import "../../static/css/index.css";

div {
  padding: 0;
  margin: 0;

}

/*banner*/

.banner {
  width: 80%;
  margin: auto;
}
</style>

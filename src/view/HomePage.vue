<template>
  <div id="HomePage">
    <div id="homeBannerOne" class="container-fuild text-center">
      <div class="text">
        <h2>あなたと</h2>
        <h2>一緒に未来を創出する</h2>
      </div>
    </div>

    <!-- 大数据管理系统 -->
    <!--    <div id="bigData" class="container-fuild">-->
    <!--      <div class="row bigData-container">-->
    <!--        <div class="col-xs-12 col-sm-12 col-md-6 wow zoomIn">-->
    <!--          <img-->
    <!--            class="img-responsive"-->
    <!--            src="@/assets/img/img1.png"-->
    <!--            alt="大数据管理系统"-->
    <!--          />-->
    <!--        </div>-->
    <!--        <div class="col-xs-12 col-sm-12 col-md-6">-->
    <!--          <h2 class="bigData-title">-->
    <!--            大数据管理系统-->
    <!--            <small>/ Big Data Management System</small>-->
    <!--          </h2>-->
    <!--          <p>-->
    <!--            当今最领先的响应式自助建站平台。无论您是普通互联网用户，还是专业网站制作人员，都能使用起飞页设计出最具专业水准的网站。想创建一个简单的单页式站点，还是一个专业的公司网站，亦或是一个别具一格的博客？起飞页可以满足您的所有需求。-->
    <!--          </p>-->
    <!--          <p>-->
    <!--            我们的流线式网页布局设计方案和可视化图文内容编辑模式让网站制作和维护成为一件轻松惬意的事。无论您是普通互联网用户，还是专业网站制作人员。-->
    <!--          </p>-->
    <!--          <h2 class="bigData-device">PC/PAD/Phone &nbsp; 全设备支持</h2>-->
    <!--          <a href="javascript:;" class="btn btn-lg btn-block btn-info"-->
    <!--          >联系我们</a-->
    <!--          >-->
    <!--        </div>-->
    <!--      </div>-->
    <!--    </div>-->

    <div id="contactUs" class="container-fuild text-center">
      <div class="container contactUs-container">
        <h1>企業理念</h1>
        <div class="contactUs-contactWay">
          <div>
            <img src="@/assets/img/icon01.png">
            <span>助力创业者追逐梦想</span>
          </div>
          <div>
            <img src="@/assets/img/icon02.png">
            <span>坚实的伙伴关系</span>
          </div>
          <div>
            <img src="@/assets/img/icon03.png">
            <span>社会影响力和可持续发展</span>
          </div>
        </div>
        <button
          class="btn btn-default btn-sm"
          onmouseleave="this.style.borderColor='#a7a5a5'; this.style.backgroundColor='#a7a5a5'; this.style.color='#dcdce3';"
          onmouseenter="this.style.backgroundColor='transparent'; this.style.borderColor='#a7a5a5'; this.style.color='#a7a5a5';"
        >
          <span style="font-size:20px">详细</span>
        </button>
      </div>
    </div>


    <div id="support" class="container-fuild text-center">
      <div class="container contactUs-container">
        <h1>我们为您提供</h1>
        <div class="contactUs-contactWay">
          <div>
            <span>多元化投资方式</span>
            <ul>
              <li>设立子公司</li>
              <li>共同投资</li>
              <li>企业收购</li>
            </ul>
          </div>
          <div>
            <span>多方位创业支持</span>
            <ul>
              <li>行政</li>
              <li>管理</li>
              <li>经营</li>
              <li>设施</li>
            </ul>
          </div>
          <div>
            <span>多角度融资支持</span>
            <ul>
              <li>商业规划</li>
              <li>组织振兴</li>
              <li>技术支持</li>
            </ul>
          </div>
        </div>
        <button
          class="btn btn-default btn-sm"
          onmouseleave="this.style.borderColor='#a7a5a5'; this.style.backgroundColor='#a7a5a5'; this.style.color='#dcdce3';"
          onmouseenter="this.style.backgroundColor='transparent'; this.style.borderColor='#a7a5a5'; this.style.color='#a7a5a5';"
        >
          <span style="font-size:20px">详细</span>
        </button>
      </div>
    </div>

    <div id="contact" class="container-fuild text-center">
      <div class="container contactUs-container">
        <h1 style="margin-bottom: 50px">IRお問い合わせ</h1>
        <p>ご質問、ご相談等が御座いましたら、お電話または下記のフォームよりお問い合わせください。下記の</p>
        <p>入力フォームに必要事項を入力いただき、一週間以内に担当者よりご連絡させていただきます。</p>
        <hr class="hr-solid">
        <p>LIUFUND株式会社</p>
        <p>お電話でのお問い合わせ</p>
        <p>営業担当　XXX</p>
        <p>０００ー１１１１−２２２２</p>
        <hr class="hr-solid">

        <div class="row">
          <div class="col-xs-12 col-sm-12">
            <form class="form-horizontal" role="form">
              <div class="form-group col-md-6">
                <label for="name" class="col-sm-2 control-label">貴社名</label>
                <div class="col-sm-10 col-xs-12">
                  <input
                    type="text"
                    class="form-control"
                    id="name"
                    placeholder=""
                  />
                </div>
              </div>
              <div class="form-group col-md-6">
                <label for="email" class="col-sm-2 control-label">メールアドレス*</label>
                <div class="col-sm-10">
                  <input
                    type="text"
                    class="form-control"
                    id="email"
                    placeholder="请输入邮箱"
                  />
                </div>
              </div>
              <div class="form-group col-md-6">
                <label for="tel" class="col-sm-2 control-label">ご氏名*</label>
                <div class="col-sm-10">
                  <input
                    type="text"
                    class="form-control"
                    id="tel"
                    placeholder=""
                  />
                </div>
              </div>
              <div class="form-group col-md-6">
                <label for="tel" class="col-sm-2 control-label">フリガナ*</label>
                <div class="col-sm-10">
                  <input
                    type="text"
                    class="form-control"
                    id="jp"
                    placeholder=""
                  />
                </div>
              </div>
              <div class="form-group col-md-6">
                <label for="content" class="col-sm-2 control-label">内容</label>
                <div class="col-sm-10">
                  <textarea
                    class="form-control"
                    id="content"
                    rows="8"
                    placeholder="请输入内容"
                  ></textarea>
                </div>
              </div>
              <div class="form-group col-md-6">
                <label for="content" class="col-sm-2 control-label">添付ファイル</label>
                <div class="col-sm-10">

                </div>
              </div>
              <div class="form-group">
                <div class="col-sm-offset-2 col-sm-10" style="margin-left: 38%">
                  <button
                    class="btn btn-default btn-block"
                    @click.stop="submitForm"
                  > 送信
                  </button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>

    <!-- 为什么选择我们 -->
    <!--    <div id="whyChooseUs" class="conatiner-fuild">-->
    <!--      <div class="container">-->
    <!--        <div class="whyChooseUs-title text-center">-->
    <!--          <p>为什么选择我们的服务</p>-->
    <!--          <p>THE REASON TO CHOOSING US</p>-->
    <!--        </div>-->
    <!--        <div class="row">-->
    <!--          <div-->
    <!--            class="col-xs-12 col-sm-6 col-md-3 server-wrapper"-->
    <!--            v-for="(item, index) in serverList"-->
    <!--            :key="index"-->
    <!--          >-->
    <!--            <div-->
    <!--              class="server-block wow slideInUp"-->
    <!--              onmouseenter="this.style.color='#28f';this.style.borderColor='#28f'"-->
    <!--              onmouseleave="this.style.color='#666';this.style.borderColor='#ccc'"-->
    <!--            >-->
    <!--              <img class="center-block" :src="item.logo" alt="logo"/>-->
    <!--              <p class="text-center">{{ item.title }}</p>-->
    <!--              <div-->
    <!--                class="text-center"-->
    <!--                v-html="item.content"-->
    <!--                onmouseenter="this.style.color='#28f'"-->
    <!--                onmouseleave="this.style.color='#ccc'"-->
    <!--              ></div>-->
    <!--            </div>-->
    <!--          </div>-->
    <!--        </div>-->
    <!--      </div>-->
    <!--    </div>-->
  </div>
</template>

<script setup name="HomePage">
import WOW from 'wow.js'
import {onMounted} from 'vue'
import {Navigation, Pagination, Scrollbar, A11y, Lazy, Autoplay} from 'swiper'
import 'swiper/css'
import 'swiper/css/navigation'
import 'swiper/css/pagination'
import 'swiper/css/scrollbar'
import 'swiper/css/lazy'
import 'swiper/css/autoplay'

import img_tel from '@/assets/img/tel.png'
import img_computer from '@/assets/img/computer.png'
import img_qq from '@/assets/img/qq.png'
import img_skill from '@/assets/img/skill.png'

const modules = [Navigation, Pagination, Scrollbar, A11y, Lazy, Autoplay]

const serverList = [
  {
    logo: img_tel,
    title: '核心优势1',
    content: '<p>由专业客服提供人工服务</p>负责疑难问题和故障受理'
  },
  {
    logo: img_computer,
    title: '核心优势2',
    content: '<p>利用远程视频工具，提供协助</p>帮助客户进行调试、解决故障'
  },
  {
    logo: img_qq,
    title: '核心优势3',
    content: '<p>利用企业QQ提供在线解答</p>帮助企业快速准确解决问题和故障'
  },
  {
    logo: img_skill,
    title: '核心优势4',
    content: '<p>由技术支持工程师，负责问题解答</p>需求受理及故障受理'
  }
]

// const { proxy } = getCurrentInstance() //获取上下文实例，ctx=vue2的this
onMounted(() => {
  // console.log('mounted', proxy)
  // console.log(proxy.$wow, '------')
  /* wowjs动画 */
  new WOW({
    boxClass: 'wow',
    animateClass: 'animated',
    offset: 0,
    mobile: true,
    live: true
  }).init()
})
</script>

<style scoped>
/* 整体盒子 */
#HomePage {
  width: 100%;
}

#homeBannerOne {
  color: #fff;
  height: 800px;
  background: url('../assets/img/homePage01.png') 0 no-repeat;
  background-size: 100% 100%;
  transition: all ease 0.6s;
}

#homeBannerOne .text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

#contactUs {
  color: black;
  height: 800px;
  background: url('../assets/img/LOGORe.png') 0 0 no-repeat;
  background-size: 100% 100%;
  transition: all ease 0.6s;
}

.contactUs-container {
  padding-top: 50px;
}

.contactUs-container button {
  width: 300px;
  height: 50px;
  margin-top: 40px;
}

#contactUs .contactUs-container .contactUs-contactWay img {
  width: 200px;
  height: 200px;
  margin: 60px;
}

.contactUs-container .contactUs-contactWay {
  justify-content: space-around;
  display: flex;
  margin-top: 80px;
}

#contactUs .contactUs-container .contactUs-contactWay span {
  font-size: 30px;
  color: grey;
}

#support {
  color: black;
  height: 600px;
  background-size: 100% 100%;
  transition: all ease 0.6s;
}

#support .contactUs-container .contactUs-contactWay span {
  font-size: 30px;
  color: black;
}

#support .contactUs-container .contactUs-contactWay li {
  font-size: 20px;
  color: black;
}

#contactUs .contactUs-container .contactUs-contactWay div:nth-of-type(1) {
  /*background: url('../assets/img/icon01.png') 0 0 no-repeat;*/
  background-size: 100% 100%;
}

#contactUs .contactUs-container .contactUs-contactWay div:nth-of-type(2) {
  /*background: url('../assets/img/icon02.png') 0 0 no-repeat;*/
  background-size: 100% 100%;
}

#contactUs .contactUs-container .contactUs-contactWay div:nth-of-type(3) {
  /*background: url('../assets/img/icon03.png') 0 0 no-repeat;*/
  background-size: 100% 100%;
}

#contact {
  color: black;
  height: 1000px;
  background-color: #F0F0F0;
  background-size: 100% 100%;
  transition: all ease 0.6s;
}
#contact .contactUs-container p{
  font-size:20px;
  font-weight: lighter;
}
.hr-solid {
  border: 0;
  border-top: 1px solid black;
}

/* 媒体查询（手机） */
@media screen and (max-width: 768px) {
  #swiper {
    height: 200px;
  }

  #bigData {
    padding: 30px;
  }

  #bigData .bigData-title {
    font-size: 20px;
  }

  #bigData .bigData-device {
    font-size: 20px;
    margin: 10px 0 10px;
  }

  #contactUs {
    height: 200px;
    transition: all ease 0.6s;
  }

  #contactUs .contactUs-container {
    padding-top: 0;
  }

  #contactUs .contactUs-container h1 {
    font-size: 25px;
  }

  #contactUs .contactUs-container h3 {
    font-size: 18px;
  }

  #contactUs .contactUs-container button {
    width: 200px;
    height: 30px;
    margin-top: 20px;
  }

  #contactUs .contactUs-container .contactUs-contactWay span {
    display: inline-block;
    width: 28px;
    height: 28px;
    margin: 10px;
  }


  #whyChooseUs {
    padding: 20px 0;
    transition: all ease 0.6s;
  }

  #whyChooseUs .whyChooseUs-title p:nth-of-type(1) {
    font-size: 20px;
    font-weight: 700;
  }

  #whyChooseUs .whyChooseUs-title p:nth-of-type(2) {
    font-size: 12px;
  }

  #whyChooseUs .server-block {
    padding: 50px 0;
    border: 1px solid #ccc;
    border-bottom: 5px solid #ccc;
  }

  #whyChooseUs .server-block img {
    width: 48px;
    height: 48px;
  }

  #whyChooseUs .server-block > p {
    font-size: 20px;
    margin: 30px 0;
  }

  #whyChooseUs .server-block > div {
    color: #ccc;
  }
}

/* 媒体查询（平板） */
@media screen and (min-width: 768px) and (max-width: 996px) {
  #swiper {
    height: 400px;
  }

  #bigData {
    padding: 60px;
  }

  #bigData .bigData-title {
    font-size: 30px;
  }

  #bigData .bigData-device {
    font-size: 30px;
    margin: 30px 0 15px;
  }

  #contactUs {
    height: 300px;
  }

  #contactUs .contactUs-container {
    padding-top: 50px;
  }

  #contactUs .contactUs-container h1 {
    font-size: 30px;
  }

  #contactUs .contactUs-container h3 {
    font-size: 20px;
  }

  #contactUs .contactUs-container button {
    width: 300px;
    height: 50px;
    margin-top: 30px;
  }

  #contactUs .contactUs-container .contactUs-contactWay span {
    display: inline-block;
    width: 32px;
    height: 32px;
    margin: 15px;
  }

  #customer .customer-title {
    font-size: 24px;
  }

  #whyChooseUs {
    padding: 20px 0;
  }
}
</style>


<template>
  <div>
    <!-- 幻灯片 开始 -->

<div v-swiper:mySwiper="swiperOption">
    <div class="swiper-wrapper">
        <div class="swiper-slide" style="background: #040B1B;">
            <a target="_blank" href="/">
                <img src="~/assets/photo/banner/1557218340628_8B.jpg" alt="首页banner">
            </a>
        </div>
        <div class="swiper-slide" style="background: #040B1B;">
            <a target="_blank" href="/">
              <img src="~/assets/photo/banner/1557218379022_8C.jpg" alt="首页banner">
            </a>
        </div>
        <div class="swiper-slide" style="background: #040B1B;">
            <a target="_blank" href="/">
              <img src="~/assets/photo/banner/1557218401606_8D.jpg" alt="首页banner">
            </a>
        </div>
    </div>
    <div class="swiper-pagination swiper-pagination-white"></div>
    <div class="swiper-button-prev swiper-button-white" slot="button-prev"></div>
    <div class="swiper-button-next swiper-button-white" slot="button-next"></div>
</div>

<!-- 幻灯片 结束 -->
 <!-- 简介 开始 -->
<div>
  <header class="comm-title">
            <h2 class="tac">
              <span class="c-333">实验室简介</span>
            </h2>
          </header>
          <div class="jianjie fsize18 c-666">Dre@mTech团队是华北电力大学为适应工业新时代发展
需求，校企联合成立，依托于计算机系、自动化系、数理系、电子系优势资源，
致力于智能计算与电力物联领域的应用开发和技术服务，不断提高承担重大科研
项目的能力和服务于电力工业的水平。一方面通过计算机技术提升电力生产、运
行、管理效率，另一方面通过计算机技术在电力工业中的应用，研究计算机技术
的需求方向，促进对计算机本体理论的研究。本团队拥有良好的科研基础条件和
设施，拥有一支知识和年龄结构合理、团结协作、富于进取精神的研究开发与技
术服务队伍，其中专任教师15人，博士生导师1人、硕士生导师7人，教授1
人，副教授2人，高级工程师2人，讲师10人，博士10人，硕士研究生40余
人，本科生80余人。本团队既有计算机本体、电网系统和发电系统方面的专家
学者，又有计算机软件开发方面的专业技术人员，依托于成立二十年的计算机极
客组织Dreamtech工作组，具有强大的科研、工程一体化闭环解决方案能力。
目前，本团队聚焦智能电网与电力信息化、电力现货市场、物联网、大数据
技术及应用、信息安全、计算机体系结构、计算机视觉和计算机图形图像处理、
智能机器人技术及应用、数字孪生技术、边缘计算、区块链技术及应用等领域。</div>
            <section class="tac pt20">
              <a href="#" title="全部课程" class="comm-btn c-btn-2">更多</a>
            </section>
</div>



 <!-- 简介 结束 -->
       <div id="aCoursesList">
      <!-- 网校课程 开始 -->
      <!-- <div>
        <section class="container">
          <header class="comm-title">
            <h2 class="tac">
              <span class="c-333">热门课程</span>
            </h2>
          </header>
          <div>
            <article class="comm-course-list">
              <ul class="of" id="bna">
                <li>
                  <div class="cc-l-wrap">
                    <section class="course-img">
                      <img
                        src="~/assets/photo/course/1442295592705.jpg"
                        class="img-responsive"
                        alt="听力口语"
                      >
                      <div class="cc-mask">
                        <a href="#" title="开始学习" class="comm-btn c-btn-1">开始学习</a>
                      </div>
                    </section>
                    <h3 class="hLh30 txtOf mt10">
                      <a href="#" title="听力口语" class="course-title fsize18 c-333">听力口语</a>
                  </h3>
                    <section class="mt10 hLh20 of">
                      <span class="fr jgTag bg-green">
                        <i class="c-fff fsize12 f-fA">免费</i>
                      </span>
                      <span class="fl jgAttr c-ccc f-fA">
                        <i class="c-999 f-fA">9634人学习</i>
                        |
                        <i class="c-999 f-fA">9634评论</i>
                      </span>
                    </section>
                  </div>
                </li>
                <li>
                  <div class="cc-l-wrap">
                    <section class="course-img">
                      <img
                        src="~/assets/photo/course/1442295581911.jpg"
                        class="img-responsive"
                        alt="Java精品课程"
                      >
                      <div class="cc-mask">
                        <a href="#" title="开始学习" class="comm-btn c-btn-1">开始学习</a>
                      </div>
                    </section>
                    <h3 class="hLh30 txtOf mt10">
                      <a href="#" title="Java精品课程" class="course-title fsize18 c-333">Java精品课程</a>
                    </h3>
                    <section class="mt10 hLh20 of">
                      <span class="fr jgTag bg-green">
                        <i class="c-fff fsize12 f-fA">免费</i>
                      </span>
                      <span class="fl jgAttr c-ccc f-fA">
                        <i class="c-999 f-fA">501人学习</i>
                        |
                        <i class="c-999 f-fA">501评论</i>
                      </span>
                    </section>
                  </div>
                </li>
                <li>
                  <div class="cc-l-wrap">
                    <section class="course-img">
                      <img
                        src="~/assets/photo/course/1442295604295.jpg"
                        class="img-responsive"
                        alt="C4D零基础"
                      >
                      <div class="cc-mask">
                        <a href="#" title="开始学习" class="comm-btn c-btn-1">开始学习</a>
                      </div>
                    </section>
                    <h3 class="hLh30 txtOf mt10">
                      <a href="#" title="C4D零基础" class="course-title fsize18 c-333">C4D零基础</a>
                    </h3>
                    <section class="mt10 hLh20 of">
                      <span class="fr jgTag bg-green">
                        <i class="c-fff fsize12 f-fA">免费</i>
                      </span>
                      <span class="fl jgAttr c-ccc f-fA">
                        <i class="c-999 f-fA">300人学习</i>
                        |
                        <i class="c-999 f-fA">300评论</i>
                      </span>
                    </section>
                  </div>
                </li>
                <li>
                  <div class="cc-l-wrap">
                    <section class="course-img">
                      <img
                        src="~/assets/photo/course/1442302831779.jpg"
                        class="img-responsive"
                        alt="数学给宝宝带来的兴趣"
                      >
                      <div class="cc-mask">
                        <a href="#" title="开始学习" class="comm-btn c-btn-1">开始学习</a>
                      </div>
                    </section>
                    <h3 class="hLh30 txtOf mt10">
                      <a href="#" title="数学给宝宝带来的兴趣" class="course-title fsize18 c-333">数学给宝宝带来的兴趣</a>
                    </h3>
                    <section class="mt10 hLh20 of">
                      <span class="fr jgTag bg-green">
                        <i class="c-fff fsize12 f-fA">免费</i>
                      </span>
                      <span class="fl jgAttr c-ccc f-fA">
                        <i class="c-999 f-fA">256人学习</i>
                        |
                        <i class="c-999 f-fA">256评论</i>
                      </span>
                    </section>
                  </div>
                </li>
                <li>
                  <div class="cc-l-wrap">
                    <section class="course-img">
                      <img
                        src="~/assets/photo/course/1442295455437.jpg"
                        class="img-responsive"
                        alt="零基础入门学习Python课程学习"
                      >
                      <div class="cc-mask">
                        <a href="#" title="开始学习" class="comm-btn c-btn-1">开始学习</a>
                    </div>
                    </section>
                    <h3 class="hLh30 txtOf mt10">
                      <a
                        href="#"
                        title="零基础入门学习Python课程学习"
                        class="course-title fsize18 c-333"
                      >零基础入门学习Python课程学习</a>
                    </h3>
                    <section class="mt10 hLh20 of">
                      <span class="fr jgTag bg-green">
                        <i class="c-fff fsize12 f-fA">免费</i>
                      </span>
                      <span class="fl jgAttr c-ccc f-fA">
                        <i class="c-999 f-fA">137人学习</i>
                  |
                        <i class="c-999 f-fA">137评论</i>
                      </span>
                    </section>
                  </div>
                </li>
                <li>
                  <div class="cc-l-wrap">
                    <section class="course-img">
                      <img
                        src="~/assets/photo/course/1442295570359.jpg"
                        class="img-responsive"
                        alt="MySql从入门到精通"
                      >
                      <div class="cc-mask">
                        <a href="#" title="开始学习" class="comm-btn c-btn-1">开始学习</a>
                      </div>
                    </section>
                    <h3 class="hLh30 txtOf mt10">
                      <a href="#" title="MySql从入门到精通" class="course-title fsize18 c-333">MySql从入门到精通</a>
                    </h3>
                    <section class="mt10 hLh20 of">
                      <span class="fr jgTag bg-green">
                        <i class="c-fff fsize12 f-fA">免费</i>
                      </span>
                      <span class="fl jgAttr c-ccc f-fA">
                        <i class="c-999 f-fA">125人学习</i>
                        |
                        <i class="c-999 f-fA">125评论</i>
                      </span>
                    </section>
                  </div>
                </li>
                <li>
                  <div class="cc-l-wrap">
                  <section class="course-img">
                      <img
                        src="~/assets/photo/course/1442302852837.jpg"
                        class="img-responsive"
                        alt="搜索引擎优化技术"
                      >
                      <div class="cc-mask">
                        <a href="#" title="开始学习" class="comm-btn c-btn-1">开始学习</a>
                      </div>
                    </section>
                    <h3 class="hLh30 txtOf mt10">
                      <a href="#" title="搜索引擎优化技术" class="course-title fsize18 c-333">搜索引擎优化技术</a>
                    </h3>
                    <section class="mt10 hLh20 of">
                      <span class="fr jgTag bg-green">
                        <i class="c-fff fsize12 f-fA">免费</i>
                      </span>
                      <span class="fl jgAttr c-ccc f-fA">
                        <i class="c-999 f-fA">123人学习</i>
                        |
                        <i class="c-999 f-fA">123评论</i>
                      </span>
                    </section>
                  </div>
                </li>
                <li>
                  <div class="cc-l-wrap">
                    <section class="course-img">
                      <img
                        src="~/assets/photo/course/1442295379715.jpg"
                        class="img-responsive"
                        alt="20世纪西方音乐"
                      >
                      <div class="cc-mask">
                        <a href="#" title="开始学习" class="comm-btn c-btn-1">开始学习</a>
                      </div>
                    </section>
                    <h3 class="hLh30 txtOf mt10">
                      <a href="#" title="20世纪西方音乐" class="course-title fsize18 c-333">20世纪西方音乐</a>
                    </h3>
                    <section class="mt10 hLh20 of">
                      <span class="fr jgTag bg-green">
                        <i class="c-fff fsize12 f-fA">免费</i>
                      </span>
                      <span class="fl jgAttr c-ccc f-fA">
                        <i class="c-999 f-fA">34人学习</i>
                        |
                        <i class="c-999 f-fA">34评论</i>
                      </span>
                    </section>
                  </div>
                </li>
              </ul>
              <div class="clear"></div>
            </article>
            <section class="tac pt20">
              <a href="#" title="全部课程" class="comm-btn c-btn-2">全部课程</a>
            </section>
          </div>
        </section>
      </div> -->
      <!-- /网校课程 结束 --> 
      <!-- 成员风采 开始 -->
      <div>
        <section class="container">
          <header class="comm-title">
            <h2 class="tac">
              <span class="c-333">成员风采</span>
            </h2>
          </header>
          <div>
            <article class="i-teacher-list">
              <ul class="of">
                <li>
                  <section class="i-teach-wrap">
                    <div class="i-teach-pic">
                      <a href="/teacher/1" title="姚晨">
                        <img class="img" alt="姚晨" src="~/assets/photo/teacher/1442297885942.jpg">
                      </a>
                    </div>
                    <div class="mt10 hLh30 txtOf tac">
                      <a href="/teacher/1" title="姚晨" class="fsize18 c-666">姚晨</a>
                    </div>
                    <div class="hLh30 txtOf tac">
                      <span class="fsize14 c-999">北京师范大学法学院副教授</span>
                    </div>
                    <div class="mt15 i-q-txt">
                      <p
                        class="c-999 f-fA"
                      >北京师范大学法学院副教授、清华大学法学博士。自2004年至今已有9年的司法考试培训经验。长期从事司法考试辅导，深知命题规律，了解解题技巧。内容把握准确，授课重点明确，层次分明，调理清晰，将法条法理与案例有机融合，强调综合，深入浅出。</p>
                    </div>
                  </section>
                </li>
                <li>
                  <section class="i-teach-wrap">
                    <div class="i-teach-pic">
                      <a href="/teacher/1" title="谢娜">
                        <img class="img"  alt="谢娜" src="~/assets/photo/teacher/1442297919077.jpg">
                      </a>
                    </div>
                    <div class="mt10 hLh30 txtOf tac">
                      <a href="/teacher/1" title="谢娜" class="fsize18 c-666">谢娜</a>
                    </div>
                    <div class="hLh30 txtOf tac">
                      <span class="fsize14 c-999">资深课程设计专家，专注10年AACTP美国培训协会认证导师</span>
                    </div>
                    <div class="mt15 i-q-txt">
                      <p
                        class="c-999 f-fA"
                      >十年课程研发和培训咨询经验，曾任国企人力资源经理、大型外企培训经理，负责企业大学和培训体系搭建；曾任专业培训机构高级顾问、研发部总监，为包括广东移动、东莞移动、深圳移动、南方电网、工商银行、农业银行、民生银行、邮储银行、TCL集团、清华大学继续教育学院、中天路桥、广西扬翔股份等超过200家企业提供过培训与咨询服务，并担任近50个大型项目的总负责人。</p>
                    </div>
                  </section>
                </li>
                <li>
                  <section class="i-teach-wrap">
                    <div class="i-teach-pic">
                      <a href="/teacher/1" title="刘德华">
                        <img class="img"  alt="刘德华" src="~/assets/photo/teacher/1442297927029.jpg">
                      </a>
                    </div>
                    <div class="mt10 hLh30 txtOf tac">
                     <a href="/teacher/1" title="刘德华" class="fsize18 c-666">刘德华</a>
                    </div>

                    <div class="hLh30 txtOf tac">

                      <span class="fsize14 c-999">上海师范大学法学院副教授</span>
                </div>
                    <div class="mt15 i-q-txt">
                      <p
                        class="c-999 f-fA"
                      >上海师范大学法学院副教授、清华大学法学博士。自2004年至今已有9年的司法考试培训经验。长期从事司法考试辅导，深知命题规律，了解解题技巧。内容把握准确，授课重点明确，层次分明，调理清晰，将法条法理与案例有机融合，强调综合，深入浅出。</p>
                    </div>

                  </section>

                </li>

                <li>

                  <section class="i-teach-wrap">
                    <div class="i-teach-pic">
                      <a href="/teacher/1" title="周润发">
                        <img class="img" alt="周润发" src="~/assets/photo/teacher/1442297935589.jpg">
                      </a>
                    </div>
                    <div class="mt10 hLh30 txtOf tac">
                      <a href="/teacher/1" title="周润发" class="fsize18 c-666">周润发</a>
                    </div>
                    <div class="hLh30 txtOf tac">
                      <span class="fsize14 c-999">考研政治辅导实战派专家，全国考研政治命题研究组核心成员。</span>
                    </div>
                    <div class="mt15 i-q-txt">
                      <p  class="c-999 f-fA"
                      >法学博士，北京师范大学马克思主义学院副教授，专攻毛泽东思想概论、邓小平理论，长期从事考研辅导。出版著作两部，发表学术论文30余篇，主持国家社会科学基金项目和教育部重大课题子课题各一项，参与中央实施马克思主义理论研究和建设工程项目。</p>
                    </div>
                  </section>

                </li>

              </ul>

              <div class="clear"></div>

            </article>

            <section class="tac pt20">

              <a href="#" title="全部成员风采" class="comm-btn c-btn-2">更多风采</a>

            </section>

          </div>

        </section>

      </div>

      <!-- 成员风采 结束 -->
     <!--  研究人员开始 -->
 <div>
        <section class="container">
          <header class="comm-title">
            <h2 class="tac">
              <span class="c-333">研究人员</span>
            </h2>
          </header>
          <div>
            <article class="i-teacher-list">
              <ul class="of">
                <li>
                  <section class="i-teach-wrap">
                    <div class="i-teach-pic">
                      <a href="/teacher/1" title="姚晨">
                        <img class="img1" alt="姚晨" src="~/assets/photo/teacher/1442297885942.jpg">
                      </a>
                    </div>
                    <div class="mt10 hLh30 txtOf tac">
                      <a href="/teacher/1" title="姚晨" class="fsize18 c-666">姚晨</a>
                    </div>
                    <div class="hLh30 txtOf tac">
                      <span class="fsize14 c-999">北京师范大学法学院副教授</span>
                    </div>
                    
                  </section>
                </li>
                <li>
                  <section class="i-teach-wrap">
                    <div class="i-teach-pic">
                      <a href="/teacher/1" title="谢娜">
                        <img class="img1" alt="谢娜" src="~/assets/photo/teacher/1442297919077.jpg">
                      </a>
                    </div>
                    <div class="mt10 hLh30 txtOf tac">
                      <a href="/teacher/1" title="谢娜" class="fsize18 c-666">谢娜</a>
                    </div>
                    <div class="hLh30 txtOf tac">
                      <span class="fsize14 c-999">资深课程设计专家，专注10年AACTP美国培训协会认证导师</span>
                    </div>
                    
                  </section>
                </li>
                <li>
                  <section class="i-teach-wrap">
                    <div class="i-teach-pic">
                      <a href="/teacher/1" title="刘德华">
                        <img class="img1" alt="刘德华" src="~/assets/photo/teacher/1442297927029.jpg">
                      </a>
                    </div>
                    <div class="mt10 hLh30 txtOf tac">
                     <a href="/teacher/1" title="刘德华" class="fsize18 c-666">刘德华</a>
                    </div>

                    <div class="hLh30 txtOf tac">

                      <span class="fsize14 c-999">上海师范大学法学院副教授</span>
                </div> 
                  </section>
                </li>
                <li>
                  <section class="i-teach-wrap">
                    <div class="i-teach-pic">
                      <a href="/teacher/1" title="周润发">
                        <img  class="img1" alt="周润发" src="~/assets/photo/teacher/1442297935589.jpg">
                      </a>
                    </div>
                    <div class="mt10 hLh30 txtOf tac">
                      <a href="/teacher/1" title="周润发" class="fsize18 c-666">周润发</a>
                    </div>
                    <div class="hLh30 txtOf tac">
                      <span class="fsize14 c-999">考研政治辅导实战派专家，全国考研政治命题研究组核心成员。</span>
                    </div>
                  </section>
                </li>
              </ul>
              <div class="clear"></div>
            </article>
          </div>

        </section>

      </div>
<!-- 研究人员结束 -->

    </div>

  </div>

</template>
<script>

export default {

  data () {
    return {
      swiperOption: {
        //配置分页
        pagination: {
          el: '.swiper-pagination'//分页的dom节点
        },
        autoHeight: true,
        loop:true,
        //配置导航
        navigation: {
          nextEl: '.swiper-button-next',//下一页dom节点
          prevEl: '.swiper-button-prev'//前一页dom节点
        },
        autoplay: {
          delay: 3000,
          disableOnInteraction: false,

},
      }
    }
  }
}

</script>
<style>
.jianjie{
  padding: 0 40px;
  line-height: 35px;
  text-indent:2em;
}
.i-teach-pic .img1{display:block;border-radius:1%;max-width:120%;}
</style>
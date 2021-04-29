<template>
  <div class="in-wrap">
    <!-- 公共头引入 -->
    <header id="header">
      <section class="container">
        <h1 id="logo">
          <a href="#" title="Dre@mTech实验室">
            <img src="~/assets/img/logo.png" width="110%" alt="Dre@mTech实验室">
          </a>
        </h1>
        <div class="h-r-nsl">
          <ul class="nav">
            <router-link to="/" tag="li" active-class="current" exact>
              <a>首页</a>
            </router-link>
            <router-link to="/course" tag="li" active-class="current">
              <a>研究团队</a>
            </router-link>
            <router-link to="/teacher" tag="li" active-class="current">
              <a>研究方向</a>
            </router-link>
            <router-link to="/article" tag="li" active-class="current">
              <a>项目成果</a>
            </router-link>
            <router-link to="/qa" tag="li" active-class="current">
              <a>成员风采</a>
            </router-link>
             <router-link to="/qa" tag="li" active-class="current">
              <a>联系我们</a>
            </router-link>
          </ul>
          <!-- / nav -->
       
        </div>
        <aside class="mw-nav-btn">
          <div class="mw-nav-icon"></div>
        </aside>
        <div class="clear"></div>
      </section>
    </header>
    <!-- /公共头引入 -->
      
    <nuxt/>

    <!-- 公共底引入 -->
    <footer id="footer">
      <section class="container">
        <div class>
          <h4 class="hLh30">
            <span class="fsize18 f-fM c-ccc">友情链接</span>
          </h4>
          <ul class="of flink-list">
            <li>
              <a href="https://cs.ncepu.edu.cn/szzk/yjsds/wlhjkyznfxyjz/5ca6571e67a74182ba34eae6c0992c3b.htm" title="华北电力大学计算机系" target="_blank">华北电力大学计算机系</a>
            </li>
          </ul>
          <div class="clear"></div>
        </div>
        <div class="b-foot">
          <section class="fl col-7">
            <section class="mr20">
              <section class="b-f-link">
            
                <span>电话：010-56253825</span>|
                <span>邮编：071100</span>|
                <span>Email：info@.com</span>

              </section>
              <section class="b-f-link mt10">
                <span>版权所有©Dre@mTech实验室</span>
              </section>
            </section>
          </section>
          
          <div class="clear"></div>
        </div>
      </section>
    </footer>
    <!-- /公共底引入 -->
  </div>
</template>
<script>
import "~/assets/css/reset.css";
import "~/assets/css/theme.css";
import "~/assets/css/global.css";
import "~/assets/css/web.css";

export default {};
</script>
<style scoped>
.h-r-nsl .nav{
margin-left: 30px;
}
</style>
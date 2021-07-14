<template>
  <div class="header">
    <div class="wrap header-wrap clearfix">
      <h1 class='logo fl'>
        网易云音乐
        <a href='javascript:;'>
        </a>
      </h1>
      <ul class="fl clearfix">
        <li><nuxt-link to='/'>首页</nuxt-link></li>
        <li><nuxt-link to='/my'>我的音乐</nuxt-link></li>
        <li><nuxt-link to='/friend'>朋友</nuxt-link></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Banner'
}
</script>

<style scoped lang="scss">
  .header-wrap {
    ul {
      li {
        float: left;
        height: 70px;
        font-size: 14px;
        text-align: center;

        a {
          padding: 0 19px;
          text-align: center;
          display: block;
          width: 100%;
          line-height: 70px;
        }
      }:hover {
         color: #fff;
         background: #000;
       }

    }
  }
  .header {
    background: #242424;
    ul li {
      a {
        color: #ccc;
      }
    }
  }
  .logo {
    background: url("https://s2.music.126.net/style/web2/img/frame/topbar.png?424eb3a62b3c5b5d51b08f7fc248a421") no-repeat  0 0 ;
    width:176px;
    height: 69px;
    text-indent: -999em;
  }
</style>

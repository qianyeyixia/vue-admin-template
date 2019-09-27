<template>
  <div class="footer">
    <p class="footer__copyright">
      本系统由
      <a href="http://vchaoxi.com/" target="_blank">微潮汐</a>
      提供技术支持 v2.0.0
    </p>
  </div>
</template>
<script>
export default {
  name: 'Footer'
}
</script>
<style lang='scss' scoped>
.footer {
  margin-top: 80px;
  margin-bottom:20px;
  &__copyright {
    text-align: center;
    a {
      color:#409eff;
    }
  }
}
</style>

<template>
  <section class="return-top" v-if="isShow">
    <div class="container"></div>
  </section>
</template>
<script>
export default {
  data () {
    return {
      isShow: false
    }
  },
  props () {
    element: {
    }
  },
  created () {
    let scrollEle = null
    let that = this
    scrollEle = this.element ? this.element : document.body
    scrollEle.onscroll = function () {
      that.isShow = this.scrollTop > 0 ? true : false
    }
  }
}
</script>
<style lang="less" scoped>
.return-top{
  width: 88px;
  height: 122px;
  position: fixed;
  bottom: 89px;
  right: 30px;
  background-image: url('../assets/other/returnTop.png');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
</style>

<template>
  <section class="container">
    <div class="head">
      <div class="join">
        <div class="person"></div>
        <div class="content">
          <p class="name">用户名张三</p>
          <p>今日投票剩余数 <span>3</span></p>
        </div>
        <div class="join-button">
          <div class="finish-button"></div>
        </div>
      </div>
      <div class="finish"></div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'navbar',
  data () {
    return {
    }
  },
  props: {
  },
  methods: {
  }
}
</script>
<style scoped>
.container{
  background-color: #eeeeee;
  border: 1px solid #eeeeee;
  min-height: 100vh;
}

</style>


<template>
  <section>
    <div class="top">
      <div class="text">已完成的题目数： <span class="number">1/10</span></div>
      <div class="buttons">
        <div class="my-subject-btn">我的题目</div>
        <div class="refresh-btn">刷新</div>
      </div>
    </div>
    <div class="content">
      <div class="item">
        <div class="head">
          <div class="left">
            <i class="person-photo"></i>
            <span class="name">令狐冲</span>
            <span class="icon"></span>
          </div>
          <div class="right">点击选择题目</div>
        </div>
        <div class="desc">
          <p class="title">题目：</p>
          <p class="detail">在平底锅的基础上增加了很多其他的元素，增加了吃鸡的氛围，每个人都能够吃到鸡，增加了吃鸡的气氛。</p>
        </div>
      </div>
      <div class="item">
        <div class="head">
          <div class="left">
            <i class="person-photo"></i>
            <span class="name">令狐冲</span>
            <span class="icon"></span>
          </div>
          <div class="right">点击选择题目</div>
        </div>
        <div class="desc">
          <p class="title">题目：</p>
          <p class="detail">在平底锅的基础上增加了很多其他的元素，增加了吃鸡的氛围，每个人都能够吃到鸡，增加了吃鸡的气氛。</p>
        </div>
      </div>
      <div class="item">
        <div class="head">
          <div class="left">
            <i class="person-photo"></i>
            <span class="name">令狐冲</span>
            <span class="icon"></span>
          </div>
          <div class="right">点击选择题目</div>
        </div>
        <div class="desc">
          <p class="title">题目：</p>
          <p class="detail">在平底锅的基础上增加了很多其他的元素，增加了吃鸡的氛围，每个人都能够吃到鸡，增加了吃鸡的气氛。</p>
        </div>
      </div>
    </div>

    <!-- 返回顶部 -->
    <return-top></return-top>
  </section>
</template>
<script>
import ReturnTop from './components/returnTop'
export default {
  data () {
    return {
    }
  },
  components: {
    ReturnTop
  }
}
</script>
<style lang="less" scoped>
@import '../common/css/fn.less';
.top{
  height: 110px;
  line-height: 110px;
  background-color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 0 30px;
  box-shadow: 0px 5px 4px 0px 
		rgba(0, 0, 0, 0.08);
  .text{
    font-size: 28px;
    color: #333333;
    .number{
      color: #e69801;
    }
  }
  .buttons{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    color: #ffffff;
    line-height: 80px;
    font-size: 28px;
    .my-subject-btn{
     	width: 160px;
      height: 80px;
      background-color: #e69800;
    }
    .refresh-btn{
      width: 160px;
      height: 80px;
      background-color: #343434;
      margin-left: 5px;
    }
  }
}
.content{
  .item{
    height: 218px;
    background-color: #ffffff;
    margin-top: 30px;
    .head{
      height: 68px;
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
      padding: 0 30px;
      .borderBottom1pxHeight();
      .left{
        display: flex;
        flex-direction: row;
        align-items: center;
        .person-photo{
          width: 50px;
          height: 50px;
          border-radius: 90%;
          background-color: rgb(99, 96, 96);
        }
        .name{
          color: #5c5c5c;
          font-size: 28px;
          font-weight: 800;
          margin-left: 10px;
        }
        .icon{
          display: block;
          width: 10px;
          height: 30px;
          background-color: #e69800;
          margin-left: 10px;
        }
      }
      .right{
        color: #707070;
        font-size: 28px;
      }
    }
    .desc{
      height: 150px;
      padding: 0 30px;
      font-size: 28px;
      text-align: left; 
      .title{
        font-weight: 800;
        line-height: 4px;
      }
      .detail{
        color: #737373;
      }
    }
  }
}
</style>

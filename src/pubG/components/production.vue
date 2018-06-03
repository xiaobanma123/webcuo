<template>
  <section class="container">
    <div class="head">
      <div class="join">
        <div class="person-content">
          <div class="person"></div>
          <div class="content">
            <p class="name">用户名张三</p>
            <p class="vote-desc">今日投票剩余数 <span class="number">3</span></p>
          </div>
        </div>
        <div class="join-button">
          <div class="finish-button"></div>
        </div>
      </div>
      <div class="finish">
        <div class="button-finish"></div>
      </div>
    </div>
    <div class="recommend">
      <div class="header">
        <span class="left-title">今日推荐</span>
        <div class="right-content">
          <span class="text">刷一刷</span>
          <i class="icon"></i>
        </div>
      </div>
      <div class="recommend-content">
        <div class="production-item">
          <div class="image"></div>
          <div class="item-content">
            <p class="title">绝地平底锅项链</p>
            <div class="persons">
              <div class="person1">
                <i class="person1-left"></i>
                <span class="name">张三丰</span>
              </div>
              <div class="person2">
                <i class="person2-left"></i>
                <span class="name">李特斯</span>
              </div>
            </div>
            <div class="bottom">
              <span class="label">文化</span>
              <span class="number">24351票</span>
            </div>
          </div>
        </div>
        <div class="production-item">
          <div class="image"></div>
          <div class="item-content">
            <p class="title">绝地平底锅项链</p>
            <div class="persons">
              <div class="person1">
                <i class="person1-left"></i>
                <span class="name">张三丰</span>
              </div>
              <div class="person2">
                <i class="person2-left"></i>
                <span class="name">李特斯</span>
              </div>
            </div>
            <div class="bottom">
              <span class="label">文化</span>
              <span class="number">24351票</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="ranking">
      <div class="header">
        <span class="left-title">人气排行</span>
        <div class="right-content">
          <span class="text">More</span>
          <i class="icon"></i>
        </div>
      </div>
      <div class="ranking-content">
        <div class="production-item">
          <div class="image"></div>
          <div class="item-content">
            <p class="title">绝地平底锅项链</p>
            <div class="persons">
              <div class="person1">
                <i class="person1-left"></i>
                <span class="name">张三丰</span>
              </div>
              <div class="person2">
                <i class="person2-left"></i>
                <span class="name">李特斯</span>
              </div>
            </div>
            <div class="bottom">
              <span class="label">文化</span>
              <span class="number">24351票</span>
            </div>
          </div>
        </div>
        <div class="production-item">
          <div class="image"></div>
          <div class="item-content">
            <p class="title">绝地平底锅项链</p>
            <div class="persons">
              <div class="person1">
                <i class="person1-left"></i>
                <span class="name">张三丰</span>
              </div>
              <div class="person2">
                <i class="person2-left"></i>
                <span class="name">李特斯</span>
              </div>
            </div>
            <div class="bottom">
              <span class="label">文化</span>
              <span class="number">24351票</span>
            </div>
          </div>
        </div>
                <div class="production-item">
          <div class="image"></div>
          <div class="item-content">
            <p class="title">绝地平底锅项链</p>
            <div class="persons">
              <div class="person1">
                <i class="person1-left"></i>
                <span class="name">张三丰</span>
              </div>
              <div class="person2">
                <i class="person2-left"></i>
                <span class="name">李特斯</span>
              </div>
            </div>
            <div class="bottom">
              <span class="label">文化</span>
              <span class="number">24351票</span>
            </div>
          </div>
        </div>
        <div class="production-item">
          <div class="image"></div>
          <div class="item-content">
            <p class="title">绝地平底锅项链</p>
            <div class="persons">
              <div class="person1">
                <i class="person1-left"></i>
                <span class="name">张三丰</span>
              </div>
              <div class="person2">
                <i class="person2-left"></i>
                <span class="name">李特斯</span>
              </div>
            </div>
            <div class="bottom">
              <span class="label">文化</span>
              <span class="number">24351票</span>
            </div>
          </div>
        </div>
      </div>
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
  background-color: #f4f4f4;
  border: 1px solid #f4f4f4;
  min-height: 100vh;
  color: #333333;
  font-size: 12px;
  width: 100%;
}
.container .join{
  height: 80px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  background-color: #ffffff;
}
.join .person-content{
    display: flex;
    align-items: center;
}
.join .person{
  width: 50px;
  height: 50px;
  border-radius: 90%;
  background-image: url('../assets/production/person.jpg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  margin-left: 15px;
}
.join .content{
  margin-left: 15px;
}
.join .name{
  color: #333333;
  font-size: 14px;
}
.vote-desc{
  margin-top: 10px;
  color: #666666;
  font-size: 12px;
}
.vote-desc .number{
  color: #e69800;
}
.join-button{
  width: 100px;
  height: 40px;
  margin-right: 15px;
  background-image: url('../assets/production/button01.jpg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.finish{
  margin-top: 10px;
  height: 60px;
  background-image: url('../assets/production/button02.png');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
}
.button-finish{
  width: 100px;
  height: 35px;
  margin-right: 15px;
}
.header{
  height: 59px;
  background-color: #ffffff;
  border-top: 1px solid #ffffff;
  border-bottom: 0.5px solid #e0dede;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.header .left-title{
  font-family: MicrosoftYaHei-Bold;
  color: #e69800;
  font-size: 16px;
  font-style: italic;
  margin: 26px 0 0 17px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  font-weight: 800;
}
.header .right-content{
  margin: 30px 15px 0 0;
}
.recommend .header .icon{
  display: inline-block;
  width: 14px;
  height: 14px;
  background-image: url('../assets/production/icon-shuaxin.png');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  vertical-align: bottom;
  margin-left: 3px;
}

.recommend-content{
  border: 1px solid #ffffff;
  background-color: #ffffff;
  height: 300px;
}
.production-item{
  width: 172.5px;
  height: 280px;
  margin: 10px 0 0 10px;
  float: left;
}
.production-item .image{
  width: 173px;
  height: 183px;
  background-image: url('../assets/production/production.png');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.production-item .item-content{
  width: 100%;
  height: 96px;
  background-color: #f8f8f8;
  border-top: 1px solid #f8f8f8;
}
.item-content .title{
  font-size: 16px;
  font-weight: 900;
  margin: 7px 0 0 15px;
  text-align: left;
}
.item-content .persons{
  display: flex;
  flex-direction: row;
  margin-top: 8px;
}
.item-content .person1 .person1-left{
  display: inline-block;
  width: 5px;
  height: 13px;
  background-color: #e69800;
  margin-left: 15px;
}
.item-content .person2 .person2-left{
  display: inline-block;
  width: 5px;
  height: 13px;
  background-color: #8ca223;
  margin-left: 30px;
}
.item-content .bottom{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-top: 13px;
}
.item-content .bottom .label{
  width: 40px;
  height: 19px;
  background-color: #333333;
  border-radius: 4px;
  color: #ffffff;
  margin-left: 15px;
}
.item-content .bottom .number{
  font-size: 13px;
  color: #afafaf;
  margin-right: 12px;
}
.ranking{
  margin-top: 10px;
}
.ranking-content{
  border: 1px solid #ffffff;
  background-color: #ffffff;
  height: 590px;
}
.ranking .header .icon{
  display: inline-block;
  width: 14px;
  height: 14px;
  background-image: url('../assets/production/icon_more.png');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  vertical-align: bottom;
  margin-left: 3px;
}
</style>


<template>
  <section>
    <div class="head">
      <head-logo></head-logo>
      <navbar v-model="selected" :list="navbarList"></navbar>
    </div>
    
    <mt-tab-container v-model="selected">
      <mt-tab-container-item id="1">
        <home-page></home-page>
      </mt-tab-container-item>
      <mt-tab-container-item id="2">
        <rules></rules>
      </mt-tab-container-item>
      <mt-tab-container-item id="3">
        <production></production>
      </mt-tab-container-item>
      <mt-tab-container-item id="4">
        <mt-cell v-for="n in 6" :title="'选项 ' + n"  :key="n"/>
      </mt-tab-container-item>
    </mt-tab-container>
  </section>
</template>

<script>
import HeadLogo from './components/headLogo'
import Navbar from './components/navbar'
import HomePage from './components/homePage'
import Production from './components/production'
import Rules from './components/rules'
export default {
  name: 'page-navbar',
  components:{
    HeadLogo,
    Navbar,
    HomePage,
    Production,
    Rules
  },
  data() {
    return {
      selected: '1',
      navbarList: [{text: '首页', id: '1'},
                {text: '赛事规则', id: '2'},
                {text: '参赛作品', id: '3'},
                {text: '获奖介绍', id: '4'}]
    };
  }
};
</script>
<style scoped>
.head{
  background-color: #333333;
}
</style>


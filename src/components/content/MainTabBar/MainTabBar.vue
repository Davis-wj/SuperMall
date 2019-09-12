<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <img slot="item-icon" src="~assets/img/tabbar/首页.svg" alt />
      <img slot="item-icon-active" src="~assets/img/tabbar/首页-A.svg" alt />
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category">
      <img slot="item-icon" src="~assets/img/tabbar/分类.svg" alt />
      <img slot="item-icon-active" src="~assets/img/tabbar/分类-A.svg" alt />
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <img slot="item-icon" src="~assets/img/tabbar/购物车.svg" alt />
      <img slot="item-icon-active" src="~assets/img/tabbar/购物车-A.svg" alt />
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <img slot="item-icon" src="~assets/img/tabbar/用户.svg" alt />
      <img slot="item-icon-active" src="~assets/img/tabbar/用户-A.svg" alt />
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template> 

<script>
import TabBar from "components/common/tab-bar/TabBar";
import TabBarItem from "components/common/tab-bar/TabBarItem"
export default {
  name: "MainTabBar",
  components: {
      TabBar,
      TabBarItem
  }
};
</script>

<style>
</style>
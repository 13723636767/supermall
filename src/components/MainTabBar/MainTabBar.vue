<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="black">
      <div slot="item-icon"><img src="../../assets/img/tabbar/home.svg" alt=""></div>
      <div slot="item-icon-active"><img src="../../assets/img/tabbar/home_active.svg" alt=""></div>
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="black">
      <div slot="item-icon"><img src="../../assets/img/tabbar/category.svg" alt=""></div>
      <div slot="item-icon-active"><img src="../../assets/img/tabbar/category_active.svg" alt=""></div>
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/shopcart" activeColor="black">
      <div slot="item-icon"><img src="../../assets/img/tabbar/shopcart.svg" alt=""></div>
      <div slot="item-icon-active"><img src="../../assets/img/tabbar/shopcart_active.svg" alt=""></div>
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="black">
      <div slot="item-icon"><img src="../../assets/img/tabbar/profile.svg" alt=""></div>
      <div slot="item-icon-active"><img src="../../assets/img/tabbar/profile_active.svg" alt=""></div>
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>

</template>

<script>
import TabBarItem from '../TabBar/TabBarItem'
import TabBar from '../TabBar/TabBar'
export default {
  name: "MainTabBar",
  components: {
  TabBarItem,
  TabBar
  }
}
</script>

<style>

</style>
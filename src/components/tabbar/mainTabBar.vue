<!--  -->
<template>
  <div>
      <!-- @在jsconfig 文件里配置了 代表src -->
    <tabBar>
      <tabItem path="/home" activeColor="red">
        <img slot="item-icon" src="@/assets/img/tabBar/home.svg" />
        <img slot="item-active" src="@/assets/img/tabBar/home_active.svg" />
        <p slot="item-text">
          首页
        </p>
      </tabItem>
      <tabItem path="/category">
        <img slot="item-icon" src="@/assets/img/tabBar/category.svg" />
        <img
          slot="item-active"
          src="../../assets/img/tabBar/category_active.svg"
        />
        <p slot="item-text">
          分类
        </p>
      </tabItem>
      <tabItem path="/cart">
        <img slot="item-icon" src="@/assets/img/tabBar/shopcart.svg" />
        <img
          slot="item-active"
          src="@/assets/img/tabBar/shopcart_active.svg"
        />
        <p slot="item-text">
          购物车
        </p>
      </tabItem>
      <tabItem path="/profile">
        <img slot="item-icon" src="@/assets/img/tabBar/profile.svg" />
        <img
          slot="item-active"
          src="@/assets/img/tabBar/profile_active.svg"
        />
        <p slot="item-text">
          我的
        </p>
      </tabItem>
    </tabBar>
  </div>
</template>

<script>
import tabBar from "./tabbar.vue";
import tabItem from "./tabBar_Item.vue";

export default {
  data() {
    return {};
  },
  components: {
    tabBar,
    tabItem,
  },
};
</script>
<style lang="less" scoped></style>

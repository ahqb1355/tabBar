<template>
  <div id="app">
    <mainTabBar> </mainTabBar>
    <router-view></router-view>
  </div>
</template>
<script>
import mainTabBar from "./components/tabbar/mainTabBar";

// import tabBar from "./components/tabbar/tabbar";
// import tabItem from "./components/tabbar/tabBar_Item";

export default {
  data() {
    return {
      current: ""
    };
  },

  components: {
    mainTabBar
  }
};
</script>

<style lang="less">
@import "./assets/css/normalize.css";

.active {
  color: red;
}
</style>

<template>
  <div id="app">
    <!-- <keep-alive  exclude="Detail"> -->
      <router-view></router-view>
    <!-- </keep-alive> -->
    <MainTabBar />
  </div>
</template>

<script>
import MainTabBar from "components/content/mainTabbar/MainTabBar";

export default {
  name: "App",
  data() {
    return {
      isFresh:false
    };
  },
  created() {
    
    
    
  },
 
  components: {
    MainTabBar
  }
};
</script>

<style>
@import "assets/css/base.css";
</style>

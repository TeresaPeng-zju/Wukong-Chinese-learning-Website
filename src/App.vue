<template>
  <div id="app">
    <TopBar></TopBar>
    <router-view />
  </div>
</template>

<script>
import TopBar from "@/components/TopBar.vue";
export default {
  name: "HomeView",
  components: {
    TopBar,
  },
};
</script>

<style lang="less">
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
// }
</style>

<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
    <div class="test"></div>
    <test></test>
  </div>
</template>

<script>
import test from "./components/test"
export default {
  name: 'app',
  components:{
    test
  }
}
</script>

<style lang="less">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  .test{
    width:100%;
    height:80px;
    background: red;
  }
}
</style>

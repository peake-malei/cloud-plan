<template>
  <div id="app">
    <img alt="Vue logo" style="height:200px" src="http://peake-img.peake.com.cn/logo/20171026/00367a54af7f45b4b6553896dc595f25.png">
   <!-- <img alt="Vue logo" src="./assets/logo.png">-->
  <!--  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <CloudPlan />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

import CloudPlan from './components/CloudPlan.vue'

export default {
  name: 'app',
  components: {
    CloudPlan
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>

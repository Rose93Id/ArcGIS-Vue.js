<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <SyriaPop />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import SyriaPop from "./components/SyriaPop.vue";

export default {
  name: "App",
  components: {
    //HelloWorld
    SyriaPop
  }
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}
#app {
  display: flex;
  flex-direction: column;
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100%;
}
</style>

<template>
  <img alt="Vue logo" src="./assets/61485693.png" style="width: 200px;height:200px;border: 1px;border-radius: 20px 20px 20px 20px">
  <HelloWorld msg="个人介绍"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

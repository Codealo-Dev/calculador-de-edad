<template>
  <img alt="Codealo logo" src="./assets/logo.png">
  <HelloWorld msg="[Project Name]"/>
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
  color: #011627;
  margin-top: 60px;
}
</style>

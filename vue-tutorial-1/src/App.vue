<template>
  <div id="app">
    <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="I Love Vue.js" msg2="I Love You More"/>
  </div>
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

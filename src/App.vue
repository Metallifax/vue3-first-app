<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <useless-button/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import UselessButton from './components/UselessButton'

export default {
  name: 'App',
  components: {
    HelloWorld,
    UselessButton
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

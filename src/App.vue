<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <FirstPage msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import FirstPage from './components/FirstPage.vue'

export default {
  name: 'App',
  components: {
    FirstPage
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
}
</style>

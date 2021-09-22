<template>
  <SplashPage msg="Welcome to Your Vue.js App"/>
</template>

<script>
import SplashPage from './components/SplashPage.vue'

export default {
  name: 'App',
  components: {
    SplashPage
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

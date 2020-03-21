<template>
  <div id="app">
    <landing-page/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import LandingPage from './components/LandingPage.vue'

export default {
  name: 'App',
  components: {
    "landing-page": LandingPage,
  }
}
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;

}
</style>

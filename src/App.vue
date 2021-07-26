<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    Home
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cookie&family=Raleway:wght@500&display=swap');
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: #2a3b40;
}
</style>

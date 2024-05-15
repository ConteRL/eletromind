<template>
  <NavBar />
  <Welcome />
  <Quote/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Welcome from './components/Welcome.vue'
import Quote from './components/Quote.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Welcome,
    Quote
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

  width: 100vw;
  height: 100vh;
}
</style>

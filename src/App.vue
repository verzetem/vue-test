<template>
  <div id="app">
    <NavBar/>
    <HelloWorld helloProps="Welcome to puppy paradise!!"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/Nav.vue'
import Puppies from './components/Puppies.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    NavBar,
    Puppies
  }
}
</script>

<style>
body {
  background-color: #0F1315;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

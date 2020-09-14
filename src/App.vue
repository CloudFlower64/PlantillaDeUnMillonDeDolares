<template>
  <div id="app">
    <NavBar/>
    <Search/>
    <Profesores/>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Huanito UWU"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/Navbar.vue'
import Profesores from './components/Profesores'
import Search from './components/Search'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavBar,
    Profesores,
    Search,
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
  background: gainsboro;
}
</style>

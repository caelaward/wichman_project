<template>
<NavComp/>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/service">Service</router-link> |
    <router-link to="/projects">Our Work</router-link> |
    <router-link to="/contact">Contact</router-link> 
  </nav> -->
  <router-view/>
</template>

<script>
import NavComp from './components/NavComp.vue'
export default {
  components:{
    NavComp
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
  overflow: hidden;
  background-color: beige;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>

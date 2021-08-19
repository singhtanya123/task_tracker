<template>
<div id="app">   
  <Navbar/>  
  <Home msg="Hi Everyone... "/>  
  <Personality class="describe"> 
    <h3> Vue js || JavaScript || HTML || CSS || SCSS</h3>
    <p>My current personal website lacked ~personality~... So I decided it was time for a new one. Watch me build the front-end of my new personal website FROM SCRATCH in less than 10 minutes using Vue.js, HTML, and CSS!</p>
  </Personality>
  </div>  
</template>

<script>
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import Personality from './components/Personality.vue'

export default {
  name: 'App',
  components: {
    Home,
    Navbar,
    Personality
  }
}
</script>

<style >

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;  
}

</style>

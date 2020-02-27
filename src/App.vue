<template>
  <div class="container-fluid p-0">
    <Nav/>
    <Intro/>
    <Academics/>
    <Hobbies/>
    <Sports/>
    <Gallery/>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Intro from './components/Intro.vue'
import Academics from './components/Academics.vue'
import Hobbies from './components/Hobbies.vue'
import Sports from './components/Sports.vue'
import Gallery from './components/Gallery.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Intro,
    Academics,
    Hobbies,
    Sports,
    Gallery
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

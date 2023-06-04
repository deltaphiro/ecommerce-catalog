<template>
  <NavBar/>
  <!-- <HelloWorld msg="Woi Bro!"/> -->
  <MenSection/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue';
import MenSection from './components/MenSection.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    NavBar,
    MenSection
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 0;
  text-align: center;
}
</style>

<template>
    <div class="app">
      <Navbar />
      <Jumbotron />
      <CTA />
    </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Jumbotron from './components/Jumbotron.vue';
import CTA from './components/CTA.vue';
export default {
  name: "App",
  components: {
    Navbar,
    Jumbotron,
    CTA,
  },
};
</script>

<style>
  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align:center;
    color: #2c3e50;

  }

</style>

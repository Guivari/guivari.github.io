<script setup lang="ts">
import Navbar from 'components/general/Navbar.vue'
import NavBar2 from 'components/general/NavBar2.vue'
import Landing from 'components/pages/Landing.vue'
import Footer from 'components/general/Footer.vue' 

</script>

<template>
  
  <NavBar2 />

  <Landing msg="Vite + Vue" />

  <Footer msg="All Rights Reserved." />

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

</style>

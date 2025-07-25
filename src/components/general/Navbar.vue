
<script setup lang="ts">


</script>

<template>
  <nav class="navbar">
    <div class="nav-left">
      <a href=""><img class="logo" src="assets/Logo_Light.png" alt=""></a>
      <a href="">ABOUT</a>
      <a href="">PROJECTS</a>
      <a href="">BLOG</a>
    </div>
    <div class="nav-right">
      <a href="">Contact me!</a>
    </div>
  </nav>
  <div class="spacer"></div>
</template>

<style scoped>
.spacer {
  height: 5em;
}
.navbar {
  position: fixed;
  top: 0;
  width: 100%;
  background-color: #666;
  display: flex;
  justify-content: space-between;
  height: 5em;
  border-bottom: 1px solid #444;  
}
.nav-left {
  height: 100%;
  display: flex;
  font-size: 2em;
  align-items: center;
}
.nav-left a {
  color: white;
  padding: 0 1em 0 0;
}
.nav-right {
  height: 100%;
  display: flex;
  font-size: 2em;
  align-items: center;
}
.nav-right a {
  color: white;
  padding: 0 1em 0 0;
}
.nav-left a:first-child {
  height: 100%;
  display: flex;
  align-items: center;
  padding-left: 1em;
}
.logo {
  max-height: 60%;
}
</style>

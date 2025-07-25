<script setup lang="ts">
import ArticlePreviewLarge from 'components/articlePreview/ArticlePreviewLarge.vue' 

defineProps<{ msg: string }>()

</script>

<template>
  <div class="hero">
    <div class="container">
      <div class="hero-header">
        <div class="header-picture">
          <img src="assets/me_5.jpg" alt="">
        </div>
        <div class="header-text">
          <h3>Hi hello, I'm Guivari Amri, this is my portfolio! (Still working on it!!!)</h3>
          <h3>Get to know me! You'll learn about my work, my writing and my hobbies. Check out some of my work here!</h3>
        </div>
      </div>
      <div class="hero-content">
        <ArticlePreviewLarge />
      </div>
    </div>

  </div>
</template>

<style scoped>
.hero {
  display: flex;
  background: url("assets/hero_bg.jpg");
  background-repeat: no-repeat;
  height: 90vh;
  background-attachment: fixed; 
  background-size: 100% auto;
}
.container {
  width: 100%;
  margin: 0 3em;
  /* background-color: rgba(255, 255, 255, 0.2); */
  display: flex;
}
.hero-header {
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  width: 30%;
  margin: 2em;
  /* background-color: rgba(255, 255, 255, 0.2); */
}
.header-picture {
  padding: 0 2em;
}
.header-picture img {
  background: red;
  height: 16em;
  border-radius: 50%;
}
.hero-content {
  margin: 2em;
  display: flex;
  flex-direction: column;
  width: 70%;
  background-color: rgba(0, 0, 0, 0.2);
}
</style>

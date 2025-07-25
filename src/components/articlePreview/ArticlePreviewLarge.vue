<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <div class="articlePreview">
    <div class="article-header">
      <h1>Header</h1>
    </div>
    <div class="article-content">
      <div class="article-abstract">
        <p>Abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract abstract</p>
      </div>
      <div class="article-footer">
        <div class="article-categories">
          <div>category</div>
          <div>category</div>
          <div>category</div>
        </div>
        <div class="readmore">
          <h3>Read more!</h3>
        </div>
      </div>
    </div>
  </div>
</template>


<style scoped>
.articlePreview {
  background-color: #ddd;
  height: 100%;
  display: flex;
  flex-direction: column;
}
.article-content {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.article-footer {
  display: flex;
  justify-content: space-between;
}
.article-categories {
  display: flex;
}
</style>
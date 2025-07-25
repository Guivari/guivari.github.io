<script setup lang="ts">
import Hero from 'components/general/Hero.vue' 

defineProps<{ msg: string }>()

</script>

<template>
  <Hero />
</template>

<style scoped>
.main {
  background: #333;
}
</style>

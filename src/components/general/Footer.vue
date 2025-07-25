<script setup lang="ts">

defineProps<{ msg: string }>()

</script>

<template>
  <div class="footer">
    <h1> &copy; {{ new Date().getFullYear() }} Guivari Amri. {{ msg }}</h1>
  </div>
</template>

<style scoped>
.footer {
  font-size: 4pt;
}
</style>

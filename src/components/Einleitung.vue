<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="einleitung">
    <h3 class="green">{{ msg }}</h3>
  </div>
</template>

<style scoped>
.einleitung {
  text-align: center;
  padding: 3rem;
}
</style>

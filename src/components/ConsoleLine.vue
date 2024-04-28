<script setup lang="ts">
defineProps<{
  maxLength: number
  text: string
}>()
</script>

<template>
  <div class="console-line">
    <h4 class="green">{{ text }}</h4>
  </div>
</template>

<style scoped>
h4 {
  font-weight: 500;
  font-size: 1.2rem;
  position: relative;
  top: -10px;
}
</style>

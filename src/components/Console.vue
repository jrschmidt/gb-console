<script setup lang="ts">
import ConsoleLine from './ConsoleLine.vue'

defineProps<{
  maxLength: number
  text: string
}>()
</script>

<template>
  <div class="console">
    <ConsoleLine
      max-length="80"
      text="10 REM MAX IS 80 CHARACTERS"
    />
    <ConsoleLine
      max-length=80
      text="80 REM AN 80 CHARACTER LINE ..12345678901234567890123456789012345678901234567890"
    />
  </div>
</template>

<style scoped>
.console {
  position: relative;
  top: 30px;
  padding: 10px;
  border: 2px white solid;
}
</style>

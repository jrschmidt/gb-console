<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import ConsoleLine from './components/ConsoleLine.vue'
</script>

<template>
  
  <main>
    <HelloWorld msg="gb-console" />
    <ConsoleLine
      max-length="80"
      text="10 REM MAX IS 80 CHARACTERS"
    />
    <ConsoleLine
      max-length="80"
      text="80 REM AN 80 CHARACTER LINE ..12345678901234567890123456789012345678901234567890"
    />
  </main>
</template>

<style scoped>
</style>

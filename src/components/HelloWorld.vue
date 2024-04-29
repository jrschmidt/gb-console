<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="hello-world">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Configurable console emulator in a Vue component suitable for use in GB80 apps
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
  bottom: 20px;
}

h3 {
  font-size: 1.2rem;
}

.hello-world h1,
.hello-world h3 {
  text-align: center;
}
</style>

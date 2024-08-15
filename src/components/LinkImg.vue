<template>
  <a :href="link" target="_blank" style="display: grid; width: fit-content; margin: auto;">
    <img :src="img" />
  </a>
</template>

<script setup lang="ts">

defineProps<{ link: string, img: string }>()

</script>

<style scoped>
img {
  transition: .5s all;
  width: 80%;
  max-width: 600px;
  margin: 20px auto;
}

img:hover {
  scale: 1.1;
}
</style>

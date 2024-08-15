<template>
  <h3 id="AHeaderCont">
    <div style="padding: 20px;">
      {{ text }}
    </div>
  </h3>
</template>

<script setup lang="ts">

defineProps<{ text: string }>()

</script>

<style scoped>
#AHeaderCont {
  text-align: center;
  transition: all .3s;
  background: linear-gradient(to right, rgb(0, 255, 255, .3), rgb(255, 0, 255, .3));
  padding: 10px;
  font-weight: 600;
}

#AHeaderCont * {
  border: 10px solid rgba(255, 255, 255, .5);
  transition: .3s all;
}

#AHeaderCont *:hover {
  border: 10px solid rgb(255, 255, 255, .8);
  scale: 1.012 1.04;
}
</style>

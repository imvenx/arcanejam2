<template>
  <div style="margin: auto; width: 100%; background-color: rgba(0,0,0,.75); position: absolute; top: 0; bottom: 0;">
    <router-view />
  </div>
</template>

<script setup lang="ts">
import { onMounted } from 'vue';

onMounted(() => {
  document.addEventListener('mousemove', createSparklesAroundMouse);
})

function createSparklesAroundMouse(e: MouseEvent) {
  const sparkle = document.createElement('div');
  sparkle.classList.add('sparkle');

  const size = Math.random() * 3 + 2;
  sparkle.style.width = `${size}px`;
  sparkle.style.height = `${size}px`;

  sparkle.style.left = `${e.pageX + (Math.random() - 0.5) * 10}px`;
  sparkle.style.top = `${e.pageY + (Math.random() - 0.5) * 10}px`;
  document.body.appendChild(sparkle);

  setTimeout(() => sparkle.remove(), 1000);
}
</script>

<style>
.sparkle {
  position: absolute;
  border-radius: 50%;
  box-shadow: 0 0 20px 2px #fff;
  pointer-events: none;
  animation: fadeOut 1s forwards;
  border: 1px solid white;
  opacity: 1;
}

@keyframes fadeOut {
  to {
    opacity: 0;
  }
}
</style>

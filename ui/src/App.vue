<script setup lang="ts">
import Hero from './views/Hero.vue';
</script>

<template>
  <Hero />
</template>

<style>
@import url("./main.scss");

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--accent);
  background-color: #d5fefd;
  background-image: radial-gradient(#d5fefd 0%, #fffcff 90%);
  display: flex;
  justify-content: center;
}
</style>

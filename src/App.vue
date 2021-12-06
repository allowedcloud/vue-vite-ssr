<script setup lang="ts">
import { useHead } from '@vueuse/head'
import TheNav from './components/TheNav.vue'
useHead({
  title: 'Vite Starter',
  meta: [
    {
      name: 'description',
      content: 'Minimal Vue 3 Vite starter template'
    }
  ]
})
</script>

<template>
  <TheNav />
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

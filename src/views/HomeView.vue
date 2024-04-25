<script setup>
import { ref } from 'vue'

const key = ref("chicago");
</script>

<template>
  <main>
    <img :src="`${baseDir}images/${fixtures[key].img}`">
    <h1>Filename: {{ fixtures[key].img }}</h1>
  </main>
</template>

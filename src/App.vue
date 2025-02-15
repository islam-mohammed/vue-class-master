<script setup lang="ts">
import { RouterView, RouterLink } from 'vue-router'
</script>

<template>
  <h1>Welcome to the application</h1>
  <RouterLink :to="{ name: '/Index' }">Home</RouterLink>
  <RouterLink :to="{ name: '/projects/' }">Projects</RouterLink>

  <RouterView />
</template>

<style scoped></style>

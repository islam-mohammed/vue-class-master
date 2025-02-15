<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <h2>Projects Page</h2>
  <RouterLink :to="{ name: '/projects/[id]', params: { id: 3 } }">Project Details</RouterLink>
</template>

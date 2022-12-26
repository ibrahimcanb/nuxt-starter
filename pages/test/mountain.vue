<script setup>
const { data: mountain } = await useFetch('/api/mountains/everest', { pick: ['title', 'description'] })
</script>
<template>
  <h1>{{ mountain.title }}</h1>
  <p>{{ mountain.description }}</p>
</template>

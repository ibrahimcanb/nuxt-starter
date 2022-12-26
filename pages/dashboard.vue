<template>
  <div>
    <h1>Welcome to your dashboard</h1>
  </div>
</template>
<script setup>
definePageMeta({
  middleware: 'auth'
});

useHead({
  titleTemplate: (titleChunk) => {
    return titleChunk ? `${titleChunk} - Site Title` : 'Site Title';
  }
})

</script>

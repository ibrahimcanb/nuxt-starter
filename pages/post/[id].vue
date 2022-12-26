<template>
  <div>xdxd</div>
</template>
<script setup>

definePageMeta({
  validate: async (route) => {
    const nuxtApp = useNuxtApp()
    // Check if the id is made up of digits
    return /^\d+$/.test(route.params.id)
  }
})
</script>

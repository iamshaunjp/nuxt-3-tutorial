<template>
  <div>
    <p>This is a dynamic route, the slug is {{ slug }}</p>
  </div>
</template>

<script setup>
  const { slug } = useRoute().params
</script>
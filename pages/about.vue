<script setup lang="ts">
const { data } = useLazyFetch("/api/hello");
</script>

<template>
  <h1>Esto es un about page</h1>
  {{ data }}
</template>

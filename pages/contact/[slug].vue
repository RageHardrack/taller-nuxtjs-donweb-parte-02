<script setup>
const route = useRoute();
</script>

<template>
  <h2>Esto es el articulo tal: {{ route.params.slug }}</h2>
</template>

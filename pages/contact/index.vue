<script setup lang="ts">
const { data } = useLazyFetch("/api/posts");
</script>

<template>
  <h2>Esto es un contact page dentro de una carpeta</h2>
  <p>Esto es una prueba</p>
  {{ data }}
</template>

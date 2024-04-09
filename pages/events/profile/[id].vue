<template>
  <div>event id: {{ $route.params.id }}</div>
</template>

<script setup lang="ts">
// const route = useRoute();
// console.log(route.params.id);

const nuxt = useNuxtApp();
console.log(nuxt);
</script>

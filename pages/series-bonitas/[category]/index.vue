<template>
  <div>
    <h1>Series de la categoría: {{ category }}</h1>
    <NuxtLink to="aventuras/episodio-1-spiderman"
      >Episodio 1 de Spiderman</NuxtLink
    >
  </div>
</template>

<script setup>
const { category } = useRoute().params;
</script>

<style lang="scss" scoped></style>

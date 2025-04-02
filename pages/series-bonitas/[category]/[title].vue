<template>
  <div>
    <h1>Categoría: aventuras</h1>
    <h1>Título: {{ title }}</h1>
  </div>
</template>

<script setup>
const { title } = useRoute().params;
</script>

<style lang="scss" scoped></style>

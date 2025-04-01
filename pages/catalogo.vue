<template>
  <header class="nav">
    <h1 class="nav__title">Bienvenido a la página Catálogo</h1>
    <NuxtLink to="/" class="nav__button">Ir a Inicio</NuxtLink>
  </header>
</template>

<script setup></script>

<style lang="scss" scoped>
$colors: (
  primary: #3498db,
  secondary: #2ecc71,
  danger: #e74c3c,
  warning: #f1c40f,
  info: #8e44ad,
  light: #ecf0f1,
  dark: #34495e,
);

.nav {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: map-get($colors, light);

  &__title {
    font-size: 2rem;
    color: map-get($colors, primary);
    margin-bottom: 1rem;
  }

  &__button {
    display: inline-block;
    padding: 0.5rem 1rem;
    background-color: map-get($colors, primary);
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1rem;
    text-decoration: none;

    &:hover {
      background-color: map-get($colors, dark);
      color: map-get($colors, light);
    }
  }
}
</style>

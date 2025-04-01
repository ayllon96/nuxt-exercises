<template>
  <section>
    <h1>nav</h1>
    <slot />
    <h1>footer</h1>
  </section>
</template>

<style scoped>
.default-layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.layout-nav {
  background-color: #f0f0f0;
  padding: 1rem;
  border-bottom: 1px solid #ddd;
}

.layout-content {
  flex: 1;
  padding: 2rem;
}

.layout-footer {
  background-color: #f0f0f0;
  padding: 1rem;
  border-top: 1px solid #ddd;
  text-align: center;
}
</style>

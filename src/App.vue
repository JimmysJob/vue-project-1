<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/Task1">進階任務 - 元件</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped>
nav {
  width: 100%;
  font-size: 16px;

  margin-top: 1rem;
}

nav a {
  display: inline-block;
  padding: 0 0.5rem;
}
</style>

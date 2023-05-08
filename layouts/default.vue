<template>
  <header>
    <nav class="container mx-auto p-4 flex justify-between">
      <NuxtLink to="/">Nuxt 3</NuxtLink>
      <ul class="flex gap-4">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products">Products</NuxtLink></li>
      </ul>
    </nav>
  </header>
  <main class="container mx-auto p-4"><slot /></main>

  <footer class="container mx-auto p-4">Footer</footer>
</template>

<script setup></script>

<style scoped></style>

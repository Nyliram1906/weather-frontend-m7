<script setup></script>

<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <router-link class="navbar-brand" to="/">El Tiempo en Scadrial</router-link>
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <router-link class="nav-link" to="/">Inicio</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <router-view />

  <footer class="container py-3 my-4">
    <p class="text-center text-body-secondary">
      © 2025 Marilyn Villalobos Rojas - Mistborn Edition
    </p>
  </footer>
</template>

<script setup>
</script>

<style scoped></style>
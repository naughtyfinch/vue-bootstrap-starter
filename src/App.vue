<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <RouterLink to="/" class="nav-item">Home</RouterLink>
          <RouterLink to="/about" class="nav-item">About</RouterLink>
        </ul>
      </div>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped></style>

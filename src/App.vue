<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="flex flex-col h-screen">
    <header class="bg-white p-4 shadow-sm">
      <h1 class="text-2xl">Medimo Deadlines</h1>
      <!-- <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->

      <!-- <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav> -->
    </header>

    <RouterView />

    <footer class="text-center py-2">
      <small>&copy; 2024 Hook88</small>
    </footer>
  </div>

</template>

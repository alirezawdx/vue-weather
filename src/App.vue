<script setup>
import Navbar from './components/Navbar.vue'
</script>

<template>
  <div class="h-screen bg-cover rainy">
    <!-- Navbar -->
    <Navbar />
    <!-- Body -->
  </div>
</template>

<style>
.rainy {
  background-image: url('./src/assets/img/rainy-sky.jpg');
}
</style>
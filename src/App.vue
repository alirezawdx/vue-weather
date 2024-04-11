<script setup>
import Navbar from './components/Navbar.vue'
import Container from './components/Container.vue'
</script>

<template>
  <div class="h-screen bg-cover rainy p-10 lg:px-24">
    <!-- Navbar -->
    <Navbar />
    <!-- Container -->
    <Container />
  </div>
</template>

<style>
.rainy {
  background-image: url('./src/assets/img/rainy-sky.jpg');
}
</style>
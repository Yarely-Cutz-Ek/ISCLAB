<script setup>
import logo from './components/logo.vue'
import esti from './components/esti.vue'

</script>

<template>
  <div class="app">
  <header>
    <logo></logo>
  </header>
  <main>
    <esti/>
  </main>
  </div>
</template>
<style>
  .app {
    background-image: url("@/assets/fondo3.jpg");
    background-size: cover;

    /* Otros estilos opcionales para ajustar la imagen de fondo */
  }
</style>

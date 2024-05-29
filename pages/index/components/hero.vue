<template>
  <div class="hero-image">
    <div class="hero-text">
      <h1 style="font-size:50px">NHOT</h1>
      <h1>Las redes flotan entre sí</h1>
      <br>
    </div>
  </div>
</template>

<script setup>
// No se necesitan funciones específicas para este ejemplo
</script>

<style>
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.hero-image {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("/fondo1x.jpg");
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.hero-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: rgb(255, 255, 255);
  font-family: Arial, sans-serif;
}
</style>
<template >
  <v-container class="background-image-container">
    <AppBar />
    <Hero />
    <Footer></Footer> 
  </v-container>
    
</template>
  
    
    <script setup>
    
    import AppBar from "./components/app-bar.vue"
    import Hero from "./components/hero.vue"
    import Footer from "./components/footer.vue"
    </script>

<style scoped>
.background-image-container {
  background-image: url('fondo1.jpg');
  background-size: contain;
  background-position: center;
}
</style>
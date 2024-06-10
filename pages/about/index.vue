<template >
  <v-container class="background-image-container">
    <AppBar />
    <Card />
    <Footer></Footer> 
  </v-container>
    
</template>
  
    
    <script setup>
    
    import AppBar from "./components/app-bar.vue"
    import Card from "./components/card.vue"
    import Footer from "./components/footer.vue"

    </script>

<style scoped>
.background-image-container {
  background-image: url('fondo1.jpg');
  background-size: contain;
  background-position: center;
  background-color: #E9E9E9 ;
}
</style>
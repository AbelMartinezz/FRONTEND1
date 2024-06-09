<template>
    <v-container class="background-image-container">
      <AppBar />
      <Secciongrupos />
      <Footer></Footer> 
    </v-container>
      
  </template>
    
      
      <script setup>
      
      import AppBar from "../../index/components/app-bar.vue"
      import Secciongrupos from "../../products/components/secciongrupos.vue"
      import Footer from "../../index/components/footer.vue"
  
      </script>
  
  <style scoped>
  .background-image-container {
    background-image: url('fondo1.jpg');
    background-size: contain;
    background-position: center;
    margin-top: 50px;
  }
  </style>
<template>
    <v-container class="background-image-container">
      <AppBar />
      <Card />
      <Card1 />
      <Card2 />
      <Card3 />
      <Card4 />
      <Footer></Footer> 
    </v-container>
      
  </template>
    
      
      <script setup>
      
      import AppBar from "../index/components/app-bar.vue"
      import Card from "./components/card.vue"
      import Card1 from "./components/card1.vue"
      import Card2 from "./components/card2.vue"
      import Card3 from "./components/card3.vue"
      import Card4 from "./components/card4.vue"
      import Footer from "../index/components/footer.vue"
  
      const items = ref([
        {
          titulo: "Producto 1",
          subtitulo: "Categoria a",
          text: "Lorem itsum"
          },
          {
            titulo: "Producto 1",
          subtitulo: "Categoria a",
          text: "Lorem itsum"
          },
          {
            titulo: "Producto 1",
          subtitulo: "Categoria a",
          text: "Lorem itsum"
          }])
  
  
      </script>
  
  <style scoped>
  .background-image-container {
    background-image: url('fondo1.jpg');
    background-size: contain;
    background-position: center;
    margin-top: 50px;
  }
  </style>
  
      
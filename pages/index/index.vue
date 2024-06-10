<template>

    <AppBar />
      <hero></hero>
      <Seccion1/>
      <Seccion2/>
      <Carousel></Carousel>
      <Footer></Footer>
</template>
   
  
    
    <script setup>
    
    import AppBar from "./components/app-bar.vue"
    import Hero from "./components/hero1.vue"
    import Seccion1 from "./components/seccion1.vue"
    import Seccion2 from "./components/seccion2.vue"
    import Carousel from "./components/carousel2.vue"
    import Footer from "./components/footer.vue"
    </script>


<style scoped>
.background-image-container {
  background-image: url('fondo1.jpg');
  background-size: contain;
  background-position: center;
  background-color: #F4F4F4 ;
}
</style>
  
    
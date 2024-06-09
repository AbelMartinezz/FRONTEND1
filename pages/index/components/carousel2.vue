<template>
  <div style="display: flex; justify-content: center; align-items: center; height: 80vh;">
    <v-carousel :height="size" :width="size" style="margin-left: 400px; margin-right: 400px;">
      <v-carousel-item
        v-for="item in items"
        :key="item.image"
        :src="item.image"
        cover
      ></v-carousel-item>
    </v-carousel>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const items = ref([
  {
    image: "/logoNHOT.png",
  },
  {
    image: "/futsal.jpeg",
  },
  {
    image: "/basket.jpeg",
  },
]);

const size = ref('500px');
</script>

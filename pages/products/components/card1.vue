<template>
  <v-card class="mx-auto my-4" max-width="344">
    <v-img height="200px" src="/mapa.jpg" cover></v-img>

    <v-card-title class="pt-4">
      {{ VCardItem.titulo }}
    </v-card-title>

    <v-card-subtitle class="pb-4">
      {{ VCardItem.subtitulo }}
    </v-card-subtitle>

    <v-card-actions class="py-4">
      <v-btn color="orange lighten-2" text :to="VCardItem.link">
        IR A
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'" @click="show = !show"></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show" class="px-4">
        <v-divider></v-divider>
        <v-card-text class="pt-4">
          {{ VCardItem.text }}
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
</template>

<script>
export default {
  data: () => ({
    show: false,
    VCardItem: {
      text: "Te permite explorar restaurantes, puestos de comida y otros establecimientos gastronómicos, comparar sus ubicaciones, horarios y calificaciones, y tomar una decisión informada sobre dónde comer.",
      titulo: "MAPA",
      subtitulo: "¿Para qué sirve?", 
      link: "./products/components/mapa"
    }
  }),
}
</script>

<style scoped>
.v-card-title,
.v-card-subtitle {
  margin-left: 16px;
  margin-right: 16px;
}
</style>

<template>
  <v-app-bar color="black" app>
    
    <v-btn text @click="goTo('/')">NHOT</v-btn>
    <v-spacer></v-spacer>
    <v-btn text @click="goTo('/about')">Acerca de</v-btn>

    <v-btn text @click="goTo('/products')">Productos</v-btn>

    <v-btn text @click="goTo('/contacts')">Mensajes</v-btn>

    <v-btn text @click="goTo('/publicaciones')">Publicaciones</v-btn>
  </v-app-bar>
</template>

<script>
export default {
methods: {
    goTo(route) {
        this.$router.push(route)
    }
}
}
</script>
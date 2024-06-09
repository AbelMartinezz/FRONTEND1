<template>
    <v-card class="mx-auto my-4" max-width="500">
      <v-container fluid>
        <v-row dense>
          <v-col
            v-for="card in cards"
            :key="card.title"
            :cols="card.flex"
          >
            <v-card>
              <v-img
                :src="card.src"
                class="align-end"
                height="200px"
                cover
              >
                <v-overlay :value="true" color="rgba(0, 0, 0, 0.5)">
                  <v-card-title class="text-white" v-text="card.title"></v-card-title>
                </v-overlay>
              </v-img>
  
              <v-card-actions>
                <v-spacer></v-spacer>
  
                <v-btn color="medium-emphasis" icon size="small">
                  <v-icon>mdi-heart</v-icon>
                </v-btn>
  
                <v-btn color="medium-emphasis" icon size="small">
                  <v-icon>mdi-bookmark</v-icon>
                </v-btn>
  
                <v-btn color="medium-emphasis" icon size="small">
                  <v-icon>mdi-share-variant</v-icon>
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-card>
  </template>
  
  <script>
  export default {
    data() {
      return {
        cards: [
          {
            title: "Card 1",
            src: "/imagen1.jpg",
            flex: 12
          },
          {
            title: "Card 2",
            src: "/imagen1.jpg",
            flex: 12
          },
          {
            title: "Card 3",
            src: "/imagen1.jpg",
            flex: 12
          },
          {
            title: "Card 4",
            src: "/imagen1.jpg",
            flex: 12
          },
          {
            title: "Card 5",
            src: "/imagen1.jpg",
            flex: 12
          }
          // Puedes añadir más tarjetas aquí
        ]
      };
    }
  };
  </script>
  
  <style>
  /* Puedes añadir estilos personalizados aquí si lo necesitas */
  </style>
  
<template>
  <br><br><br>
  <v-card class="mx-auto" max-width="600">
    <v-card-item
      class="bg-grey-darken-1"
      prepend-avatar="https://cdn.vuetifyjs.com/images/lists/2.jpg"
    >
      <v-card-title>
        <span class="text-h4">Franco Pozo</span>
      </v-card-title>
      <v-card-title>
        <span class="text-h7">Ayer: 14:25</span>
      </v-card-title>
      <template v-slot:append>
        <v-defaults-provider
          :defaults="{
            VBtn: {
              variant: 'text',
              density: 'comfortable',
            }
          }"
        >
          <v-btn icon="mdi-pencil"></v-btn>
          <v-btn icon="mdi-dots-vertical"></v-btn>
        </v-defaults-provider>
      </template>
    </v-card-item>
    <v-list>
      <v-list-item class="font-weight-black" prepend-icon="mdi-draw">
        Gran inaguración de un bonito lugar para ir a comer</v-list-item
      >

      <v-card-text class="text-medium-emphasis text-caption">
        El día de hoy, se inaugura un bonito lugar en el centro. Donde se ofrece
        comida desde la India. Con buffet de ensaldas y un pequeño parque para
        los niños.
      </v-card-text>
    </v-list>
    <v-img
      height="220"
      src="https://d1csarkz8obe9u.cloudfront.net/posterpreviews/indian-restaurant-grand-opening-design-template-fd5390d27f2d787a2f4690bff91957f0_screen.jpg?ts=1651479701"
      cover
    ></v-img>
  </v-card>
  <br />
  <v-divider inset></v-divider>
  <br />
  <v-card class="mx-auto" max-width="600">
    <v-card-item
      class="bg-grey-darken-1"
      prepend-avatar="https://cdn.vuetifyjs.com/images/lists/4.jpg"
    >
      <v-card-title>
        <span class="text-h4">Sofia Reyes</span>
      </v-card-title>
      <v-card-title>
        <span class="text-h7">Hoy: 10:25</span>
      </v-card-title>
      <template v-slot:append>
        <v-defaults-provider
          :defaults="{
            VBtn: {
              variant: 'text',
              density: 'comfortable',
            }
          }"
        >
          <v-btn icon="mdi-pencil"></v-btn>
          <v-btn icon="mdi-dots-vertical"></v-btn>
        </v-defaults-provider>
      </template>
    </v-card-item>
    <v-list>
      <v-list-item class="font-weight-black" prepend-icon="mdi-draw"
        >Cuidando nuestro jardín con esmero</v-list-item
      >
      <v-card-text class="text-medium-emphasis text-caption">
        La jardinería es una labor, que no solo, contribuyes al medio ambiente.
        Sino también, te alegra el alma y el espíritu.
      </v-card-text>
    </v-list>
    <v-img
      height="220"
      src="https://img.freepik.com/foto-gratis/mujer-joven-hermosa-que-coloca-jardin-que-sostiene-planta-tiesto_23-2147948208.jpg?t=st=1717818764~exp=1717822364~hmac=7da2458cf530dbd2767ce3fa78fe34d7c1bede1a562b8b2d8db27aa39d096ec3&w=1380"
      cover
    ></v-img>
  </v-card>
</template>

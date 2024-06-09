<template>
  <v-row justify="center">
    <v-col cols="12" md="3">
      <v-card class="rounded-pill text-center">
        <v-img
          width="250"
          cover
          src="https://lh3.googleusercontent.com/p/AF1QipO8DsyrBP4kJfNbJIc-D4S7SpiSCz6nXqUNsVIx=h305-no"
        ></v-img>
        <b>FRANCO</b>
      </v-card>
    </v-col>
    <v-col cols="12" md="3">
      <v-card class="rounded-pill text-center">
        <v-img
          width="250"
          cover
          src="https://lh3.googleusercontent.com/p/AF1QipO8DsyrBP4kJfNbJIc-D4S7SpiSCz6nXqUNsVIx=h305-no"
        ></v-img>
        <b>PAOLA</b>
      </v-card>
    </v-col>
    <v-col cols="12" md="3">
      <v-card class="rounded-pill text-center">
        <v-img
          :width="250"
          cover
          src="https://lh3.googleusercontent.com/p/AF1QipO8DsyrBP4kJfNbJIc-D4S7SpiSCz6nXqUNsVIx=h305-no"
        ></v-img>
        <b>SOFIA</b>
      </v-card>
    </v-col>
  </v-row>
  <br />
  <div style="background-color: #cccccc; height: 160px; width: 800px; margin: 0px 200px; border-radius: 50px; display: flex; align-items: center;">
  <v-row style="margin-left: 150px;">  <v-col cols="12" md="3">
      <div
        class="bg-surface-variant rounded-circle"
        style="height: 80px; width: 80px"
      ></div>
    </v-col>
    <v-col cols="12" md="6">
      <h2>20:34 minutos restantes</h2>
      7 Km restantes <br />
      Puerta: 425 <br />
    </v-col>
  </v-row>
</div>



  <br />
  <v-card class="bg-black rounded-pill" max-width="360">
    <v-card-title>
      <span class="text-h5">Calle: Socabaya esq. Mercado</span>
    </v-card-title>
  </v-card>
  <br />
  <v-row>
    <v-col cols="12" md="6">
      <v-card class="mx-right" max-width="400">
        <v-list>
          <v-list-item
            prepend-icon="mdi-account-multiple"
            title="37 800 Seguidores"
          ></v-list-item>

          <v-divider inset></v-divider>

          <v-list-item
            prepend-icon="mdi-email"
            title="CasaRural@bilbilitanos.com"
          ></v-list-item>

          <v-divider inset></v-divider>

          <v-list-item
            prepend-icon="mdi-earth"
            title="www.bilbilitanos.com"
          ></v-list-item>

          <v-divider inset></v-divider>

          <v-list-item
            prepend-icon="mdi-phone"
            title="(051) 72538907"
          ></v-list-item>

          <v-divider inset></v-divider>

          <v-list-item
            prepend-icon="mdi-message-text"
            title="Envia pronto tu mensaje"
          ></v-list-item>

          <v-divider inset></v-divider>
          <v-list-item
            prepend-icon="mdi-briefcase"
            title="Casa Rural Bilbilitanos"
          ></v-list-item>

          <v-divider inset></v-divider>

          <v-list-item
            prepend-icon="mdi-map-marker"
            title="43 Personas pasarón por aqui"
          ></v-list-item>
        </v-list>
      </v-card>
    </v-col>

    <v-col cols="12" md="6">
      <v-card class="mx-left" max-width="350">
        <v-img
          :width="400"
          aspect-ratio="16/9"
          cover
          src="https://lh3.googleusercontent.com/p/AF1QipO8DsyrBP4kJfNbJIc-D4S7SpiSCz6nXqUNsVIx=h305-no"
        ></v-img>
      </v-card>
    </v-col>
  </v-row>
</template>
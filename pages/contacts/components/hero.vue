<template>
  <br><br><br>
  <v-card>
    <v-tabs align-tabs="center" bg-color="grey darken-3" stacked>
      <v-tab value="tab-1">
        <v-icon icon="mdi-account"></v-icon>
        Amigos
      </v-tab>
      
      <v-tab value="tab-2">
        <div class="bg-grey rounded-pill" style="height: 40px; width: 200px">
          <h1>Mensajes</h1>
        </div>
      </v-tab>

      <v-tab value="tab-3">
        <v-card-item prepend-avatar="https://cdn.vuetifyjs.com/images/lists/2.jpg">
        </v-card-item>
        <span class="text-h7">Franco</span>
      </v-tab>
    </v-tabs>
  </v-card>

  <br />

  <v-card class="mx-auto" prepend-avatar="https://cdn.vuetifyjs.com/images/lists/3.jpg" subtitle="Mensajes Previos" width="800">
    <template v-slot:title>
      <span class="font-weight-black">Paola</span>
    </template>
  </v-card>

  <br />

  <v-card class="mx-auto" prepend-avatar="https://cdn.vuetifyjs.com/images/lists/2.jpg" text="Hola, como estas?" width="600">
    <template v-slot:title>
      <span class="font-weight-black">Franco</span>
    </template>
  </v-card>

  <br />

  <v-card class="mx-auto" prepend-avatar="https://cdn.vuetifyjs.com/images/lists/3.jpg" text="Nos vemos mas tarde" width="650">
    <template v-slot:title>
      <span class="font-weight-black">Paola</span>
    </template>
  </v-card>

  <br />

  <v-card class="mx-auto" prepend-avatar="https://cdn.vuetifyjs.com/images/lists/2.jpg" text="Claro a que hora?" width="600">
    <template v-slot:title>
      <span class="font-weight-black">Franco</span>
    </template>
  </v-card>

  <br />

  <v-card class="mx-auto" prepend-avatar="https://cdn.vuetifyjs.com/images/lists/3.jpg" text="A partir de las 5pm ya estaré libre" width="650">
    <template v-slot:title>
      <span class="font-weight-black">Paola</span>
    </template>
  </v-card>

  <br />
  <br />

  <div class="mt-5 d-flex align-items-center justify-content-center" style="margin: 0 20px;">
  <v-text-field
    label="Escribe un mensaje"
    outlined
    clear
    v-model="newMessage"
    style="flex: 1; margin-right: 10px;"
  />
  <v-btn fab small color="black" @click="sendMessage" >
    <v-icon>mdi-send</v-icon>
  </v-btn>
</div>
</template>
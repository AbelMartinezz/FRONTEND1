<template>
    <div>
      <v-img
        class="mx-auto my-6"
        max-width="228"
        src="/public/logoNHOT.png"
      ></v-img>
  
      <v-card
        class="mx-auto pa-12 pb-8"
        elevation="8"
        max-width="448"
        rounded="lg"
      >
        <div class="text-subtitle-1 text-medium-emphasis">
          Crea una nueva cuenta, para acceder a la aplicación:
        </div>
  
        <v-text-field
          density="compact"
          placeholder="email@dominio.com"
          prepend-inner-icon="mdi-email-outline"
          variant="outlined"
        ></v-text-field>
  
        <div
          class="text-subtitle-1 text-medium-emphasis d-flex align-center justify-space-between"
        >
          <b>Contraseña</b>
  
          <a
            class="text-caption text-decoration-none text-blue"
            href="#"
            rel="noopener noreferrer"
            target="_blank"
          >
            Olvide mi contraseña?</a
          >
        </div>
  
        <v-text-field
          :append-inner-icon="visible ? 'mdi-eye-off' : 'mdi-eye'"
          :type="visible ? 'text' : 'password'"
          density="compact"
          placeholder="Ingrese su contraseña"
          prepend-inner-icon="mdi-lock-outline"
          variant="outlined"
          @click:append-inner="visible = !visible"
        ></v-text-field>
  
        <v-card class="mb-12" color="surface-variant" variant="tonal">
          <v-card-text class="text-medium-emphasis text-caption">
            <b>Atención:</b> Después de tres intentos fallados se bloqueará su
            cuenta por 6 horas. Si tu quieres ingresar ahora, tiene la opción de
            hacer click "Olvide mi contraseña" abajo para crear una nueva
            contraseña.
          </v-card-text>
        </v-card>
  
        <v-btn class="mb-8" color="blue" size="large" variant="tonal" block>
          Ingreso
        </v-btn>
  
        <v-card-text class="text-center">
          <a
            class="text-blue text-decoration-none"
            href="#"
            rel="noopener noreferrer"
            target="_blank"
          >
            Puede Ingresar <v-icon icon="mdi-chevron-right"></v-icon>
          </a>
        </v-card-text>
      </v-card>
    </div>
  </template>
  
  <script>
    export default {
      data: () => ({
        visible: false,
      }),
    }
  </script>
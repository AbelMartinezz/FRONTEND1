<template>
  <v-container>
    <v-row justify="center">
  <v-col cols="9">
    <v-autocomplete
      :items="items"
      append-inner-icon="mdi-microphone"
      class="mx-auto"
      density="comfortable"
      menu-icon=""
      placeholder="Busqueda"
      prepend-inner-icon="mdi-magnify"
      style="max-width: 450px"
      theme="light"
      variant="solo"
      auto-select-first
      item-props
      rounded
    ></v-autocomplete>
  </v-col>
</v-row>

    <v-col justify="space-around">
      <v-row rows="auto" justify="center">
        <div class="text-center">
          <div
            style="background-color: #BBBBBB  ; height: 120px; width: 740px; border-radius: 50px; margin: 0 auto;"
          >
            <h1 style="color: #333333;">Franco</h1>
            <p style="color: #333333;">Programación, Inglés, Desarrollo Web</p>
            <v-btn style="background-color: #7FB3D5 ; height: 20px; width: 120px; border-radius: 50px; margin: 0 auto;">
              Visita mi Web
            </v-btn>
          </div>
        </div>
      </v-row>
      <br />
      <br />
      <v-row rows="auto" justify="center">
        <div class="text-center">
          <div
            style="background-color: #BBBBBB  ; height: 120px; width: 740px; border-radius: 50px; margin: 0 auto;"
          >
            <h1 style="color: #333333;">Sofia</h1>
            <p style="color: #333333;">Liderazgo, Métodos, Historia</p>
            <v-btn style="background-color: #7FB3D5 ; height: 20px; width: 120px; border-radius: 50px; margin: 0 auto;">
              Visita mi Web
            </v-btn>
          </div>
        </div>
      </v-row>
      <br />
      <br />
      <v-row rows="auto" justify="center">
        <div class="text-center">
          <div
            style="background-color: #BBBBBB  ; height: 120px; width: 740px; border-radius: 50px; margin: 0 auto;"
          >
            <h1 style="color: #333333;">Paola</h1>
            <p style="color: #333333;">Programación, Métodos, Algebra</p>
            <v-btn style="background-color: #7FB3D5 ; height: 20px; width: 120px; border-radius: 50px; margin: 0 auto;">
              Visita mi Web
            </v-btn>
          </div>
        </div>
      </v-row>
      
    </v-col>
    <br />
    <v-row justify="space-around">
      <v-col cols="auto">
        <div class="text-center">
          <div
            style="background-color: #D4E6F1; height: 200px; width: 340px; border-radius: 300px; margin: 0 auto;"
          >
            <h1>Programación</h1>
            1er: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
            2do: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
            3er: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
          </div>
        </div>
      </v-col>

      <v-col cols="auto">
        <div class="text-center">
          <div
            style="background-color: #D4E6F1; height: 200px; width: 340px; border-radius: 300px; margin: 0 auto;"
          >
          <h3>Métodos Cuantitativos <br />aplicados</h3>
            1er: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
            2do: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
            3er: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
          </div>
        </div>
      </v-col>

      <v-col cols="auto">
        <div class="text-center">
          <div
            style="background-color: #D4E6F1; height: 200px; width: 340px; border-radius: 300px; margin: 0 auto;"
          >
            <h1>Historia</h1>
            1er: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
            2do: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
            3er: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
          </div>
        </div>
      </v-col>

      <v-col cols="auto">
        <div class="text-center">
          <div
            style="background-color: #D4E6F1; height: 200px; width: 340px; border-radius: 300px; margin: 0 auto;"
          >
            <h1>Inglés</h1>
            1er: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
            2do: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
            3er: Semestre <br />
            <div
              style="background-color: #73C6B6; height: 20px; width: 120px; border-radius: 22px; margin: 0 auto; cursor: pointer;"
              @click="visitWebsite"
            >
              Visita mi Web
            </div>
          </div>
        </div>
      </v-col>



    </v-row>
  </v-container>
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'Tom' + '      ' + 'Programacion, Metodos, Algebra',
          icon: 'mdi-account',
        },
        { text: 'Audience', icon: 'mdi-account' },
        { text: 'Conversions', icon: 'mdi-flag' },
      ],
    }),
  }
</script>
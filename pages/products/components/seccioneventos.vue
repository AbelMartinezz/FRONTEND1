<template>
  <v-card>
    <v-tabs
      v-model="tab"
      align-tabs="center"
      color="deep-grey-accent-4"
    >
      <v-tab :value="1">PROGRAMACIÓN</v-tab>
      <v-tab :value="2">MÉTODOS</v-tab>
      <v-tab :value="3">EMPRESA</v-tab>
    </v-tabs>

    <v-tabs-window v-model="tab">
      <v-tabs-window-item
        v-for="n in 1"
        :key="n"
        :value="n"
      >
        <v-container fluid>
          <v-row>
            <v-col
              v-for="i in 1"
              :key="i"
              cols="12"
              md="4"
            >


            <div>
    <v-hover v-slot="{ isHovering, props }">
      <v-card
        class="mx-auto"
        max-width="344"
        v-bind="props"
      >
        <v-img src="/programacion.jpg"></v-img>

        <v-card-text>
          <h2 class="text-h6 text-black">
            PROGRAMACIÓN BACKEND
          </h2>
          Aprende a desarrollar aplicaciones web backend utilizando JavaScript, Node.js y Express.js. Domina las bases del desarrollo backend, desde la creación de APIs REST hasta el manejo de bases de datos. Conviértete en un desarrollador backend con alta demanda en la industria tecnológica.
        </v-card-text>

        <v-card-title>
          <v-rating
            :model-value="4"
            background-color="black"
            class="me-2"
            color="black"
            dense
            hover
          ></v-rating>
          <span class="text-black text-subtitle-2">4 Vistos</span>
        </v-card-title>

        <v-overlay
          :model-value="isHovering"
          class="align-center justify-center"
          scrim="#036358"
          contained
        >
          <v-btn variant="flat">Más Información</v-btn>
        </v-overlay>
      </v-card>
    </v-hover>
  </div>

            </v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>
      



      <v-tabs-window-item
        v-for="n in 2"
        :key="n"
        :value="n"
      >
        <v-container fluid>
          <v-row>
            <v-col
              v-for="i in 1"
              :key="i"
              cols="12"
              md="4"
            >


            <div>
              <v-hover v-slot="{ isHovering, props }">
                <v-card
                  class="mx-auto"
                  max-width="344"
                  v-bind="props"
                >
                  <v-img src="/metodos.jpg"></v-img>

                  <v-card-text>
                    <h2 class="text-h6 text-black">
                      MÉTODOS CUANTITATIVOS 
                    </h2>
                    Domina las integrales y su aplicación en el análisis financiero y la toma de decisiones estratégicas en el mundo empresarial. Aprende a calcular costos, optimizar inversiones, evaluar proyectos y maximizar ganancias.

                  </v-card-text>

                  <v-card-title>
                    <v-rating
                      :model-value="4"
                      background-color="black"
                      class="me-2"
                      color="black"
                      dense
                      hover
                    ></v-rating>
                    <span class="text-black text-subtitle-2">17 Vistos</span>
                  </v-card-title>

                  <v-overlay
                    :model-value="isHovering"
                    class="align-center justify-center"
                    scrim="#036358"
                    contained
                  >
                    <v-btn variant="flat" text :to="VCardItem.link">Más Información</v-btn>
                  </v-overlay>
                </v-card>
              </v-hover>
            </div>

            </v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>





      <v-tabs-window-item
        v-for="n in 3"
        :key="n"
        :value="n"
      >
        <v-container fluid>
          <v-row>
            <v-col
              v-for="i in 1"
              :key="i"
              cols="12"
              md="4"
            >


            <div>
              <v-hover v-slot="{ isHovering, props }">
                <v-card
                  class="mx-auto"
                  max-width="344"
                  v-bind="props"
                >
                  <v-img src="/empresa.jpg"></v-img>

                  <v-card-text>
                    <h2 class="text-h6 text-black">
                      MODELO BUSINESS CANVAS
                    </h2>
                    Desarrolla la habilidad de diseñar y analizar modelos de negocio innovadores y competitivos. Aprende a utilizar el lienzo Business Canvas para definir los elementos clave que impulsan el éxito empresarial.

                  </v-card-text>

                  <v-card-title>
                    <v-rating
                      :model-value="4"
                      background-color="black"
                      class="me-2"
                      color="black"
                      dense
                      hover
                    ></v-rating>
                    <span class="text-black text-subtitle-2">8 Vistos</span>
                  </v-card-title>

                  <v-overlay
                    :model-value="isHovering"
                    class="align-center justify-center"
                    scrim="#036358"
                    contained
                  >
                    <v-btn variant="flat">Más Información</v-btn>
                  </v-overlay>
                </v-card>
              </v-hover>
            </div>

            </v-col>
          </v-row>
        </v-container>
      </v-tabs-window-item>



    </v-tabs-window>
  </v-card>
</template>
<script>
  export default {
    data: () => ({
      tab: null,
    }),
  }
</script>  
  
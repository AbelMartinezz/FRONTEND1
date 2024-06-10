<template>
    <v-container>
        <div class="d-flex justify-center">
            <v-card width="675px" height="70px" color="black">
            <v-card-title class="text-h6 text-md-h5 text-lg-h4 text-center" >
                Últimas Publicaciones
            </v-card-title>
            </v-card>
        </div>
        <br>
      <v-row class="flex-child text-subtitle-2" justify="center">
        
  
        <v-col
          class="d-flex"
          cols="12"
          md="8"
        >
          <v-row class="ma-n3">
            <v-card
                class="mx-auto"
                max-width="280"
                style="background-color: #F4F4F4 ;"
            >
                <v-img
                class="align-end text-white"
                height="200"
                src="/programacion.jpg"
                cover
                >
                <v-card-title>BACKEND</v-card-title>
                </v-img>

                <v-card-subtitle class="pt-4">
                Nº 10
                </v-card-subtitle>

                <v-card-text>
                <div>Mejorar página Backend</div>

                <div>Tengo un problema, necesito ayuda conectando el backend con Postman. ¿Alguien podría ayudarme?</div>
                </v-card-text>

                <v-card-actions>
                <v-btn color="`black`" text="Compartir"></v-btn>

                <v-btn color="`black`" text="Respuestas" ></v-btn>
                </v-card-actions>
            </v-card>
  



            <v-card
                class="mx-auto"
                max-width="280"
                style="background-color: #F4F4F4 ;"
            >
                <v-img
                class="align-end text-black"
                height="200"
                src="/zara.jpg"
                cover
                >
                <v-card-title>ZARA</v-card-title>
                </v-img>

                <v-card-subtitle class="pt-4">
                    Nº 9
                </v-card-subtitle>

                <v-card-text>
                <div>Exposición</div>

                <div>Busco información sobre la propuesta de valor de Zara, especialmente en cuanto a su público objetivo y diferenciación de la competencia. ¿Podrían ayudarme a encontrar recursos o explicarme brevemente?</div>
                </v-card-text>

                <v-card-actions>
                <v-btn color="`black`" text="Compartir"></v-btn>

                <v-btn color="`black`" text="Respuestas" ></v-btn>
                </v-card-actions>
            </v-card>
  

            
          </v-row>
        </v-col>
  
       
      </v-row>
    </v-container>
  </template>
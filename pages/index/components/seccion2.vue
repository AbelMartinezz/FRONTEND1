<template>
  <br>
  <v-card justify="center" style="margin-left: 335px; margin-right: 335px;">
    <v-toolbar color="black" title="Jose Choque">
    </v-toolbar>

    <div class="d-flex flex-row">
      <v-tabs
        v-model="tab"
        color="grey"
        direction="vertical"
      >
        <v-tab prepend-icon="mdi-account" text="Personal" value="option-1"></v-tab>
      </v-tabs>

      <v-tabs-window v-model="tab">
        <v-tabs-window-item value="option-1">
          <v-card flat>
            <v-card-text>
              <p>
                Correo: jose@gmai.com
              </p>

              <p>
                Semestre: Tercero
              </p>

              <p class="mb-0">
                Carrera: Ciencia de Datos
              </p>
            </v-card-text>
          </v-card>
        </v-tabs-window-item>
      </v-tabs-window>
    </div>
  </v-card>
</template>
<script>
  export default {
    data: () => ({
      tab: 'option-1',
    }),
  }
</script>
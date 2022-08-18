<template>
  <v-container>
    <v-row justify="center"> <div class="titulo my-5">Portfolio</div></v-row>

    <v-row>
      <v-col cols="4" sm="12" md="4" xl="4">
        <v-card class="mx-auto" max-width="344">
          <v-img
            src="https://user-images.githubusercontent.com/7068806/185472652-60672f8d-5ec9-4ec3-94bd-64543b326bc9.png"
            height="200px"
            cover
          ></v-img>

          <v-card-title> Whatsapp Web </v-card-title>

          <v-card-subtitle> Clone Whatsapp Web com Vue.JS</v-card-subtitle>

          <v-card-actions>
            <v-btn
              color="orange-lighten-2"
              variant="text"
              href="https://github.com/mayconlemosCloud/UiCloneZapVue"
              target="_blank"
            >
              Explore
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
      <v-col cols="4" sm="12" md="4" xl="4">
        <v-card class="mx-auto" max-width="344">
          <v-img
            src="https://raw.githubusercontent.com/mayconlemosCloud/BootstrapVue-SPDM/main/src/assets/spdm.gif"
            height="200px"
            cover
          ></v-img>

          <v-card-title> Relação de Leitos </v-card-title>

          <v-card-subtitle>Projeto usando Vuex</v-card-subtitle>

          <v-card-actions>
            <v-btn
              color="orange-lighten-2"
              variant="text"
              href="https://github.com/mayconlemosCloud/BootstrapVue-SPDM"
              target="_blank"
            >
              Explore
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>

      <v-col cols="4" sm="12" md="4" xl="4">
        <v-card class="mx-auto" max-width="344">
          <v-img
            src="https://raw.githubusercontent.com/mayconlemosCloud/API-NETCORE/main/print/print.png"
            height="200px"
            cover
          ></v-img>

          <v-card-title>API .NET </v-card-title>

          <v-card-subtitle>.</v-card-subtitle>

          <v-card-actions>
            <v-btn
              color="orange-lighten-2"
              variant="text"
              href="https://github.com/mayconlemosCloud/API-NETCORE"
              target="_blank"
            >
              Explore
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>

    <v-row justify="end"> ...E muito mais </v-row>
  </v-container>
</template>
<script lang="ts">
export default {};
</script>

<style scoped>
.titulo {
  padding: 5px 16px;
  margin: 6px;
  font-size: 34px;
  text-shadow: 0 0 5px #68e1fd, 0 0 10px #68e1fd, 0 0 10px #68e1fd,
    0 0 10px #68e1fd, 0 0 100px #68e1fd;
  color: #fff;
}
</style>

<template>
  <v-container>
    <v-row align="center" justify="center">
      <v-col cols="12" xl="6" md="6" sm="12" class="mt-5">
        <Foto />
        <div class="titulo">Hey,I'm Maycon Lemos</div>
        <i>
          Bacharelado em Sistemas de Informação. Certificado como Técnico em
          Informática. Desenvolvedor fullstack. Responsável desenvolver
          sistemas, desde levantamento de requisitos, modelagem de dados ,
          compilação até o deploy em si do sistema. Analista e desenvolvedor a
          mais de 9 anos.
        </i>
        <ul class="theme-list">
          <li><b>From:</b> Rio de Janeiro, BR</li>
          <li><b>Lives In:</b> Nilopolis, RJ</li>
          <li><b>Age:</b> 31</li>
          <li><b>Gender:</b> Male</li>
        </ul>
      </v-col>

      <v-col cols="12" xl="6" md="6" sm="12" class="titulo mt-5">
        <img :src="SVG" alt="" srcset="" />
      </v-col>
    </v-row>
    <v-row align="center" justify="center" class="my-2">
      <v-divider></v-divider>
      <BarSkill />
    </v-row>
    <v-row>
      <v-divider />
      <Projetos />
    </v-row>
  </v-container>
  <Footer />
</template>

<script lang="ts">
import SVG from "./assets/developer.svg";
import Foto from "./components/Foto.vue";
import Footer from "./components/Footer.vue";
import BarSkill from "./components/BarSkill.vue";
import CardCurriculo from "./components/CardCurriculo.vue";
import Projetos from "./components/Projetos.vue";
export default {
  components: { BarSkill, Foto, Footer, CardCurriculo, Projetos },
  data() {
    return {
      count: 0,
      SVG,
    };
  },
};
</script>

<style lang="scss" scoped>
.titulo {
  font-size: 10vh;
}

.theme-list {
  position: relative;
  padding-left: 30px;
  list-style: none;
  z-index: 10;
}

.theme-list li {
  display: block;
  margin: 5px 0;
}

.theme-list li::before {
  content: "";
  position: absolute;
  left: 3px;
  margin: 6px 0;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background-color: #fff;
  border: 2px solid rgb(255, 7, 7);
}
</style>

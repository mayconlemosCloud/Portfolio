<template>
  <v-col>
    <v-avatar color="black" rounded size="100px">
      <v-img :src="nodeLogo" />
    </v-avatar>
  </v-col>
  <v-col>
    <v-avatar color="purple" rounded size="100px">
      <v-img :src="CsharpLogo" />
    </v-avatar>
  </v-col>
  <v-col>
    <v-avatar color="blue-grey darken-3" rounded size="100px">
      <v-img :src="awsLogo" />
    </v-avatar>
  </v-col>
  <v-col>
    <v-avatar color="light-blue" rounded size="100px">
      <v-img :src="dockerLogo" />
    </v-avatar>
  </v-col>
  <v-col>
    <v-avatar color="teal" rounded size="100px">
      <v-img :src="vueLogo" />
    </v-avatar>
  </v-col>
</template>

<script lang="ts">
import nodeLogo from "../assets/node.png";
import CsharpLogo from "../assets/Csharp_Logo.png";
import awsLogo from "../assets/awsLogo.png";
import dockerLogo from "../assets/dockerLogo.png";
import vueLogo from "../assets/vueLogo.png";
export default {
  data() {
    return { nodeLogo, CsharpLogo, awsLogo, dockerLogo, vueLogo };
  },
};
</script>

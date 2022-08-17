<template>
  <v-card color="#68e1fd">
    <v-container>
      <v-row>
        <v-col>
          <div>
            <v-btn
              v-for="icon in icons"
              :key="icon"
              class="mx-4 text-white"
              :icon="icon"
              variant="text"
              :href="
                icon == 'mdi-whatsapp'
                  ? 'https://api.whatsapp.com/send?phone=5521997913361'
                  : 'https://www.linkedin.com/in/mayconlemos/'
              "
              target="_blank"
            >
            </v-btn>
          </div>
        </v-col>
      </v-row>
    </v-container>

    <v-divider></v-divider>

    <div class="text-white d-flex justify-end">
      <strong>©</strong> {{ new Date().getFullYear() }} —
      <strong>Maycon Lemos</strong>
    </div>
  </v-card>
</template>
<script lang="ts">
export default {
  data: () => ({
    icons: ["mdi-whatsapp", "mdi-linkedin"],
  }),
};
</script>

<style></style>

<template>
  <v-footer class="bg-grey-darken-4 text-center d-flex flex-column">
    <div>
      <v-btn
        v-for="icon in icons"
        :key="icon"
        :icon="icon"
        class="mx-4"
        variant="text"
      ></v-btn>
    </div>

    <div class="pt-0">
      Estou sempre disponível, entre em contato comigo.
    </div>

    <v-divider></v-divider>

    <div>{{ new Date().getFullYear() }} — <strong>Matheus Trindade</strong></div>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: ["mdi-email", "mdi-whatsapp", "mdi-linkedin", "mdi-github"],
  }),
};
</script>
<template>
  <v-app>
    <v-app-bar app color="success" dark>
      <v-app-bar-title align="center">Most Used Words</v-app-bar-title>
    </v-app-bar>
    <v-main>
      <VHome />
    </v-main>
    <v-footer app color="success" dark></v-footer>
  </v-app>
</template>

<script>
import VHome from "@/components/VHome.vue";
export default {
  name: 'App',

  components: {
    VHome,
  },

  data: () => ({
    //
  }),
}
</script>

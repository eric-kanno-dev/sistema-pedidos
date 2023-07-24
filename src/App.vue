<template>
  <v-app> <HomeViewVue></HomeViewVue> </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import HomeViewVue from "./views/HomeView.vue";

export default Vue.extend({
  name: "App",
  components: {
    HomeViewVue,
  },
  data: () => ({
    //
  }),
});
</script>

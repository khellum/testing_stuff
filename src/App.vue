<template>
  <v-app>
    <Navigation></Navigation>
  </v-app>
</template>

<script>
import Navigation from "./components/Navigation.vue";

export default {
    name: "App",
    data: () => ({
    //
    }),
    components: { Navigation }
};
</script>

<template>
  <v-app>
    <Navbar />
    <v-main> </v-main>
  </v-app>
</template>

<script>
// @ is an alias to /src
import Navbar from "../components/Navbar.vue";

export default {
  name: "Home",
  data: () => ({}),
  components: {
    Navbar,
  },
};
</script>

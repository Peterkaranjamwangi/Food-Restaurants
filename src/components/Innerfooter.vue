<template>
  <v-footer color="primary lighten-1" padless>
    <v-row justify="center" no-gutters>
      <v-btn
        v-for="link in links"
        :key="link"
        color="white"
        text
        rounded
        class="my-2"
      >
        {{ link.link }} > {{ link.places }}
      </v-btn>
      <v-col class="primary lighten-2 py-4 text-center white--text" cols="12">
        {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    // links: [
    //   { link: "Home", places: "26 places" },
    //   { link: "About Us", places: "26 places" },
    //   { link: "Team", places: "26 places" },
    //   { link: "Services", places: "26 places" },
    //   { link: "Blog", places: "26 places" },
    //   { link: "Contact Us", places: "26 places" },
      
    // ],
  }),
};
</script>

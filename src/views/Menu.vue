<template>
  <div class="menu">
    <div>
      <template>
        <div>
          <v-breadcrumbs :items="items">
            <template v-slot:divider>
              <v-icon>mdi-chevron-right</v-icon>
            </template>
          </v-breadcrumbs>
        </div>
      </template>
    </div>
    <div py-5>
      <menu-image />
      <menudetails />
    </div>

    <order />
  </div>
</template>

<script>
import Menudetails from "../components/Menudetails.vue";
import MenuImage from "../components/MenuImage.vue";
import Order from "../components/Order.vue";

// @ is an alias to /src

export default {
  data: () => ({
    items: [
      {
        text: "Home",
        disabled: false,
        href: "./home",
      },
      {
        text: "Menu",
        disabled: true,
        href: "./menu",
      },
    ],
  }),
  name: "Menu",
  components: {
    MenuImage,
    Menudetails,
    Order,
  },
};
</script>

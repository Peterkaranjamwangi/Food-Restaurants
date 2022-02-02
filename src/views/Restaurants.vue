<template>
  <v-container py-16>
    <div class="restaurant">
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
      <div py-16>
        <v-tabs>
          <v-tab>Delivery</v-tab>
          <v-tab>Eating Out</v-tab>
          <v-tab>Night Out</v-tab>
        </v-tabs>
        <v-tabs>
          <v-spacer></v-spacer>
          <div class="float-right">
            <button
              type="button"
              class="mb-3 v-btn v-btn-elevated v-btn-bg light v-size--default primary"
            >
              <span class="v-btn__content">Filter</span>
            </button>
          </div>
        </v-tabs>
      </div>
      <div py-5>
        <constraints />
        <popular-restaurants />
      </div>
    </div>
  </v-container>
</template>

<script>
import Constraints from "../components/constraints.vue";
import PopularRestaurants from "../components/popularRestaurants.vue";

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
        text: "Restaurants",
        disabled: true,
        href: "./restaurants",
      },
    ],
  }),
  name: "Restaurant",
  components: {
    PopularRestaurants,
    Constraints,
  },
};
</script>

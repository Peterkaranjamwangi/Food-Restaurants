<template>
  <div class="home">
    <products />
    <collections />
    <cuisine />
    <popular />
  </div>
</template>

<script>
import Collections from "../components/collections.vue";
import Cuisine from "../components/Cuisine.vue";
import Popular from "../components/popular.vue";
import Products from "../components/Products.vue";
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    Products,
    Collections,
    Popular,
    Cuisine,
  },
};
</script>

<template>
  <div class="restaurant">
    <div py-5>
      <constraints />
      <popular-restaurants />
    </div>
  </div>
</template>

<script>
import Constraints from "../components/constraints.vue";
import PopularRestaurants from "../components/popularRestaurants.vue";

// @ is an alias to /src

export default {
  name: "Restaurant",
  components: {
    PopularRestaurants,
    Constraints,
  },
};
</script>

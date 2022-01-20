<template>
  <div class="Menu">
    <products />
  </div>
</template>

<script>
import Products from "../components/Products.vue";
// @ is an alias to /src

export default {
  name: "Menu",
  components: {
    Products,
  },
};
</script>

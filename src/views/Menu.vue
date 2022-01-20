<template>
  <div class="Menu">
    <menu-image />
    <Order />
  </div>
</template>

<script>
import MenuImage from "../components/MenuImage.vue";
import Order from "../components/Order.vue";

// @ is an alias to /src

export default {
  name: "Menu",
  components: {
    Order,
    MenuImage,
  },
};
</script>

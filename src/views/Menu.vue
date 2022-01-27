<template>
  <div class="menu">
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
  name: "Menu",
  components: {
    MenuImage,
    Menudetails,
    Order,
  },
};
</script>

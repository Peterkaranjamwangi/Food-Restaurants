<template>
  <div class="Menu" py-15 pd>
    <menu-image />
    <menudetails />
    <Order />
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
    Order,
    MenuImage,
    Menudetails,
  },
};
</script>

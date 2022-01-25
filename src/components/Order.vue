<template>
  <div>
    <v-tabs>
      <v-tab
        v-for="(item, index) in items"
        :class="{ active: currentTab === index }"
        @click="currentTab = index"
        :key="item"
      >
        {{ item }}</v-tab
      >
    </v-tabs>

    <v-tabs-items v-model="tab">
      <v-card flat>
        <div v-show="currentTab === 0">
          <v-card-text> tab0 content </v-card-text>
        </div>
        <div v-show="currentTab === 1">
          <v-card-text>Tab1 content</v-card-text>
        </div>
        <div v-show="currentTab === 2">
          <v-card-text><tab-1 /></v-card-text>
        </div>
      </v-card>
    </v-tabs-items>
  </div>
</template>

<script>
import tab1 from "../components/Tab1.vue";

export default {
  components: {
    tab1,
  },
  data() {
    return {
      currentTab: 0,
      tab: null,
      items: ["Order Online", "Book a Table", "Reviews"],
      text: "WElcome To THe Candy ShOP",
    };
  },
};
</script>

<style></style>

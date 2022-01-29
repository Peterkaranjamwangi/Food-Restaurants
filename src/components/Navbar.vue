<template>
  <div>
    <v-app-bar
      app
      color="#43a047"
      dark
      shrink-on-scroll
      prominentsrc="https://picsum.photos/1920/1080?random"
      fade-img-on-scroll
      scroll-threshold="500"
    >
      <v-toolbar-title>Application</v-toolbar-title>
      <template v-slot:img="{ props }">
        <v-img
          v-bind="props"
          gradient="to top right, rgba(55,236,186,.7), rgba(25,32,72,.7)"
        ></v-img>
      </template>

      <v-spacer></v-spacer>
      <div>
        <v-app-bar-nav-icon @click="drawermob = !drawermob"
          ><v-icon>mdi-dots-grid</v-icon></v-app-bar-nav-icon
        >
      </div>
    </v-app-bar>
    <v-sheet
      id="scrolling-techniques-5"
      class="overflow-y-auto"
      max-height="600"
    >
    </v-sheet>

    <v-navigation-drawer
      app
      class="float-left"
      v-model="drawermob"
      absolute
      temporary
    >
      <v-list>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title class="text-h6"> Application </v-list-item-title>
            <v-list-item-subtitle> subtext </v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-list>

      <v-divider></v-divider>

      <v-list>
        <v-list-item v-for="bar in bar" :key="bar.text" router :to="bar.route">
          <v-list-item-action>
            <v-icon> {{ bar.icon }} </v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-tittle>{{ bar.title }}</v-list-item-tittle>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
  </div>
</template>

<script>
export default {
  data: () => ({
    drawermob: false,

    bar: [
      { title: "Dashboard", icon: "mdi-view-dashboard", route: "/dashboard" },
      { title: "Photos", icon: "mdi-image", route: "/photos" },
      { title: "About", icon: "mdi-help-box", route: "/about" },
      { title: "Received", icon: "mdi-email-receive", route: "/received" },
      { title: "Sent", icon: "mdi-send", route: "/sent" },
      { title: "Trash", icon: "mdi-delete", route: "/trash" },
      { title: "Span", icon: "mdi-alert-octagon", route: "/span" },
    ],
  }),
};
</script>

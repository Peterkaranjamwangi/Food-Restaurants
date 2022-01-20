<template>
  <div>
    <v-app-bar app shrink-on-scroll>
      <v-toolbar-title>Application</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-app-bar-nav-icon @click="drawermob = !drawermob"
        ><v-icon>mdi-dots-grid</v-icon></v-app-bar-nav-icon
      >
    </v-app-bar>

    <v-navigation-drawer
      app
      class="float-left"
      v-model="drawermob"
      absolute
      temporary
      dark
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


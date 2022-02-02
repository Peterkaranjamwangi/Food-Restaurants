<template>
  <div>
    <v-app-bar
      app
      dark
      shrink-on-scroll
      prominent
      src="https://images.unsplash.com/photo-1525151498231-bc059cfafa2b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NXx8Zm9vZCUyMGRhcmt8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60"
    >
      <v-toolbar-title>FoodHub</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-title>
        <v-btn dark
          ><v-icon>mdi-account-circle</v-icon
          ><span class="hidden-sm-and-down">Account</span>
        </v-btn>

        <v-app-bar-nav-icon @click="drawermob = !drawermob"
          ><v-icon>mdi-cart-outline</v-icon>(9)</v-app-bar-nav-icon
        >
        <v-app-bar-nav-icon
          @click="drawermob = !drawermob"
        ></v-app-bar-nav-icon>
      </v-toolbar-title>
    </v-app-bar>

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
      { title: "Dashboard", route: "/dashboard" },
      { title: "Photos", route: "/photos" },
      { title: "About", route: "/about" },
      { title: "Received", route: "/received" },
      { title: "Sent", route: "/sent" },
      { title: "Trash", route: "/trash" },
      { title: "Span", route: "/span" },
    ],
  }),
};
</script>

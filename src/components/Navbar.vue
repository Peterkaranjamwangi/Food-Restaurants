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
      <template v-slot:img="{ props }">
        <v-img
          v-bind="props"
          gradient="to top right, rgba(55,236,186,.7), rgba(25,32,72,.7)"
        ></v-img>
      </template>
      <div>
        <div class="container d-flex align-center" data-v-42ba0752="">
          <a href="/" class="nuxt-link-active" data-v-42ba0752=""
            ><div
              class="v-avatar me-10 rounded-0"
              style="height: 48px; min-width: 48px; width: 48px"
              data-v-42ba0752=""
            >
              <img
                src="/_nuxt/img/logo.4a3964e.png"
                alt=""
                data-v-42ba0752=""
              /></div
          ></a>
          <div
            class="form-location flex-grow-1 d-none d-md-flex border rounded"
            data-v-42ba0752=""
          >
            <div class="d-flex align-center ps-5" data-v-42ba0752="">
              <i
                aria-hidden="true"
                class="v-icon notranslate v-icon--left mdi mdi-map-marker theme--light"
                style="font-size: 16px"
                data-v-42ba0752=""
              ></i>
              <span class="grey--text text--darken-1 me-3" data-v-42ba0752=""
                >New York</span
              >
            </div>
            <button
              type="button"
              class="text-capitalize rounded-0 v-btn v-btn--icon v-btn--round v-btn--text v-btn--tile theme--light v-size--large"
              data-v-42ba0752=""
            >
              <span class="v-btn__content"
                ><i
                  aria-hidden="true"
                  class="v-icon notranslate mdi mdi-crosshairs-gps theme--light"
                  style="font-size: 16px"
                  data-v-42ba0752=""
                ></i
              ></span>
            </button>
            <input
              placeholder="Search for restaurant "
              class="white flex-grow-1 ps-5"
              data-v-42ba0752=""
            />
            <button
              type="button"
              class="rounded-l-0 text-capitalize v-btn v-btn--icon v-btn--round v-btn--tile theme--light v-size--large"
              data-v-42ba0752=""
            >
              <span class="v-btn__content"
                ><i
                  aria-hidden="true"
                  class="v-icon notranslate mdi mdi-magnify theme--light"
                  style="font-size: 16px"
                  data-v-42ba0752=""
                ></i
              ></span>
            </button>
          </div>
          <div class="spacer" data-v-42ba0752=""></div>
          <div role="dialog" class="v-dialog__container" data-v-42ba0752="">
            <!---->
          </div>
          <button
            type="button"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            class="v-btn v-btn--text theme--light v-size--default"
            data-v-42ba0752=""
          >
            <span class="v-btn__content"
              ><i
                aria-hidden="true"
                class="v-icon notranslate me-0 me-sm-3 mdi mdi-account-circle-outline theme--light"
                data-v-42ba0752=""
              ></i>
              <span class="d-none d-sm-block" data-v-42ba0752=""
                >Account</span
              ></span
            >
          </button>
          <button
            type="button"
            class="me-2 v-btn v-btn--text v-btn--tile theme--light v-size--default"
            data-v-42ba0752=""
          >
            <span class="v-btn__content"
              ><i
                aria-hidden="true"
                class="v-icon notranslate mdi mdi-cart-outline theme--light"
                style="font-size: 16px"
                data-v-42ba0752=""
              ></i
              >(8)
            </span>
          </button>
          <button
            type="button"
            text=""
            light=""
            class="v-app-bar__nav-icon v-btn v-btn--icon v-btn--round v-btn--text theme--light v-size--default"
            data-v-42ba0752=""
          >
            <span class="v-btn__content"
              ><i
                aria-hidden="true"
                class="v-icon notranslate mdi mdi-menu theme--light"
                data-v-42ba0752=""
              ></i
            ></span>
          </button>
        </div>
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

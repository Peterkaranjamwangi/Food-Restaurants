<template>
  <div>
    <div class="bg-grey-light py-16">
      <div class="container">
        <div class="d-flex justify-center flex-wrap">
          <div
            class="v-image v-responsive mb-3 me-8 theme--light"
            style="max-width: 185px"
          >
            <div
              class="v-responsive__sizer"
              style="padding-bottom: 198.165%"
            ></div>
            <div
              class="v-image__image v-image__image--cover"
              style="
                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/App.4927ff9.png');
                background-position: center center;
              "
            ></div>
            <div class="v-responsive__content" style="width: 218px"></div>
          </div>
          <div class="d-flex flex-column">
            <h1 class="text-40 mb-0">Get the Mobile App</h1>
            <p class="text-18 grey--text text--darken-1 mb-0">
              We will send you a link, open it on your phone to download the app
            </p>
            <div>
              <v-row>
                <v-col xm="6" sm="3" md="3">
                  <v-radio-group column>
                    <v-radio label="Email" value="Email"></v-radio>
                  </v-radio-group>
                </v-col>
                <v-col xm="6" sm="3" md="3">
                  <v-radio-group column>
                    <v-radio label="Phone" value="Phone"></v-radio>
                  </v-radio-group>
                </v-col>
              </v-row>
            </div>
            <div class="d-flex align-center mb-8">
              <div class="v-input rounded outlined v-text-field--placeholder">
                <v-text-field
                  label="Email"
                  placeholder="email"
                  outlined
                ></v-text-field>
              </div>
              <button
                type="button"
                class="rounded-l-0 py-5 v-btn v-size--default primary"
              >
                <span class="v-btn__content"> Search </span>
              </button>
            </div>
            <h6 class="mb-3 grey--text font-weight-regular">
              Download App from
            </h6>
            <div class="d-flex flex-wrap">
              <div
                class="v-avatar me-4 rounded-0"
                style="height: 50px; min-width: 48px; width: 150px"
              >
                <img
                  src="https://lh3.googleusercontent.com/cjsqrWQKJQp9RFO7-hJ9AfpKzbUb_Y84vXfjlP0iRHBvladwAfXih984olktDhPnFqyZ0nu9A5jvFwOEQPXzv7hr3ce3QVsLN8kQ2Ao=s0"
                  alt=""
                />
              </div>
              <div
                class="v-avatar rounded-0"
                style="height: 50px; min-width: 48px; width: 150px"
              >
                <img
                  src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg"
                  alt=""
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="py-16">
      <div class="container">
        <div class="row">
          <div class="col-xl-12 col">
            <h2 class="mb-5">Popular Localities In &amp; Around New York</h2>
            <br />
            <div class="row">
              <div
                class="mb-3 col-sm-6 col-md-6 col-xm-3 col-lg-3 col-xl-3 col-12"
                v-for="link in links"
                :key="link.title"
                router
                :to="link.route"
              >
                <a href="/restaurants" class="text-decoration-none black--text"
                  >{{ link.title }}
                  <span class="grey--text">{{ link.places }}</span></a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    links: [
      { title: "Manhattan", places: "(16 places)", route: "/resturant" },
      { title: "Queens", places: "(36 places)", route: "/resturant" },
      { title: "Brooklyn", places: "(12 places)", route: "/resturant" },
      { title: "Staten Island", places: "(26 places)", route: "/resturant" },
      {
        title: " Saratoga Springs",
        places: "(4 places)",
        route: "/resturant",
      },
      { title: " Rochester", places: "(6 places)", route: "/resturant" },
      { title: "Syracuse", places: "(10 places)", route: "/resturant" },
      { title: "Rome", places: "(8 places)", route: "/resturant" },
      { title: "Manhattan", places: "(16 places)", route: "/resturant" },
      { title: "Queens", places: "(36 places)", route: "/resturant" },
      { title: "Brooklyn", places: "(12 places)", route: "/resturant" },
      { title: "Staten Island", places: "(26 places)", route: "/resturant" },
      {
        title: " Saratoga Springs",
        places: "(4 places)",
        route: "/resturant",
      },
      { title: " Rochester", places: "(6 places)", route: "/resturant" },
      { title: "Syracuse", places: "(10 places)", route: "/resturant" },
      { title: "Rome", places: "(8 places)", route: "/resturant" },
      { title: "Manhattan", places: "(16 places)", route: "/resturant" },
      { title: "Queens", places: "(36 places)", route: "/resturant" },
      { title: "Brooklyn", places: "(12 places)", route: "/resturant" },
      { title: "Staten Island", places: "(26 places)", route: "/resturant" },
      {
        title: " Saratoga Springs",
        places: "(4 places)",
        route: "/resturant",
      },
      { title: " Rochester", places: "(6 places)", route: "/resturant" },
      { title: "Syracuse", places: "(10 places)", route: "/resturant" },
      { title: "Rome", places: "(8 places)", route: "/resturant" },
    ],
  }),
};
</script>

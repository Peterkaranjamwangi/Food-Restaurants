<template>
  <div class="grey lighten-3">
    <v-container py-15 >
      <h1>Collections</h1>
      <p>
        Explore curated lists of top restaurants, cafes, pubs, and bars in New
        York, based on trends
      </p>
      <br />
      <v-row dense>
        <v-col
          cols="12"
          sm="6"
          md="3"
          v-for="card in collections"
          :key="card.title"
        >
          <v-card router :to="card.route">
            <v-img
              :src="card.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="200px"
            >
              <v-card-title v-text="card.title"></v-card-title>
              <div class="d-flex" router :to="card.route">
                <p class="text-sm white--text mb-0">30 Places</p>
                <i
                  aria-hidden="true"
                  class="v-icon notranslate mdi mdi-chevron-right theme--light white--text"
                  style="font-size: 16px"
                ></i>
              </div>
            </v-img>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data: () => ({
    collections: [
      {
        title: "Most Searched of 2022",
        src: "https://images.unsplash.com/photo-1504754524776-8f4f37790ca0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8N3x8Zm9vZHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
        route: "/about",
      },
      {
        title: "Best Openings of 2022",
        src: "https://images.unsplash.com/photo-1473093295043-cdd812d0e601?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fGZvb2R8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60",
        flex: 12,
        route: "/about",
      },
      {
        title: "Trending This Week",
        src: "https://images.unsplash.com/photo-1529042410759-befb1204b468?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTd8fGZvb2R8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60",
        flex: 12,
        route: "/about",
      },
      {
        title: "Best Of New York",
        src: "https://images.unsplash.com/photo-1506368249639-73a05d6f6488?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
        route: "/about",
      },
    ],
  }),
};
</script>

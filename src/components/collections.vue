<template>
  <div>
    <v-container py-15 pd>
      <h1>Collections</h1>
      <p>
        Explore curated lists of top restaurants, cafes, pubs, and bars in New
        York, based on trends
      </p>
      <br />
      <v-row dense>
        <v-col v-for="card in collections" :key="card.title" cols="12" md="4">
          <v-card>
            <v-img
              :src="card.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="200px"
            >
              <v-card-title v-text="card.title"></v-card-title>
              <div class="d-flex">
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
        title: "Pre-fab homes",
        src: "https://images.unsplash.com/photo-1504754524776-8f4f37790ca0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8N3x8Zm9vZHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
        route: "/files",
      },
      {
        title: "Favorite road trips",
        src: "https://images.unsplash.com/photo-1473093295043-cdd812d0e601?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fGZvb2R8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60",
        flex: 12,
        route: "/files",
      },
      {
        title: "Best airlines",
        src: "https://images.unsplash.com/photo-1529042410759-befb1204b468?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTd8fGZvb2R8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60",
        flex: 12,
        route: "/files",
      },
    ],
  }),
};
</script>

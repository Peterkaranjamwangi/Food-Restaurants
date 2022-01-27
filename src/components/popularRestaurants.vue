<template>
  <div class="grey lighten-3">
    <v-container>
      <h1>184 Delivery Restaurants in New York</h1>
      <br />
      <v-row dense>
        <v-col
          v-for="card in popular"
          :key="card.title"
          cols="12"
          sm="6"
          md="4"
        >
          <a href="#" class="text-decoration-none black--text"
            ><v-card>
              <div
                class="br-10 o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
              >
                <div class="position-relative">
                  <v-img
                    :src="card.src"
                    class="white--text align-end"
                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                    height="200px"
                  >
                  </v-img>
                  <div>
                    <span
                      draggable="false"
                      flat=""
                      class="p-absolute top-0 rounded-r-xl rounded-l-0 mt-3 v-chip v-chip--label theme--light v-size--default primary"
                      ><span class="v-chip__content">Flat 30% Off</span></span
                    >
                  </div>
                </div>
                <div class="pa-4 d-flex justify-space-between align-center">
                  <span
                    class="d-inline-block text-truncate me-3 f-600 text-18 card-title"
                    v-text="card.title"
                  ></span>
                  <div class="d-flex align-center card-rating">
                    <i
                      aria-hidden="true"
                      class="v-icon notranslate me-1 mdi mdi-star theme--light yellow--text text--darken-2"
                      style="font-size: 16px"
                    ></i>
                    <div>
                      <span class="font-weight-bold text-14">4.5</span>
                      <span class="grey--text text--darken-1 text-14">/5</span>
                    </div>
                  </div>
                </div>
                <p class="px-4 grey--text text--darken-1">
                  <span
                    class="primary--text f-600 me-1"
                    v-text="card.price"
                  ></span>
                  • Cofee, set menu • 15 - 20 min
                </p>
              </div>
            </v-card></a
          >
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data: () => ({
    rating: 4.3,
    popular: [
      {
        title: "Starbucks",
        src: "https://images.unsplash.com/photo-1532634922-8fe0b757fb13?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8N3x8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.3,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$$20",
        flex: 12,
      },
      {
        title: "Bonefish Grill",
        src: "https://images.unsplash.com/photo-1543353071-087092ec393a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.6,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$35",
        flex: 12,
      },
      {
        title: " Gnocchi",
        src: "https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjB8fGZvb2QlMjBhbmQlMjBkcmlua3xlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.1,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$15",
        flex: 12,
      },
      {
        title: " O'Charley's",
        src: "https://media.istockphoto.com/photos/food-with-high-content-of-omega3-fats-picture-id1301412050?b=1&k=20&m=1301412050&s=170667a&w=0&h=nViB9ZIwyVRLPD5s123i48XNq_MNUvdBtX3IzAHnqec=",
        rating: 4.6,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$45",
        flex: 12,
      },
      {
        title: "Yard House",
        src: "https://images.unsplash.com/photo-1540189549336-e6e99c3679fe?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Zm9vZHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.4,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$50",
        flex: 12,
      },
      {
        title: "Maggiano's Little Italy",
        src: "https://images.unsplash.com/photo-1498837167922-ddd27525d352?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8Zm9vZHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.5,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$25",
        flex: 12,
      },
    ],
  }),
};
</script>

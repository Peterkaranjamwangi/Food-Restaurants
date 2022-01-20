<template>
  <div>
    <v-container py-15 pd>
      <h1>Popular Near You</h1>
      <br />
      <v-row dense>
        <v-col v-for="card in popular" :key="card.title" cols="12" md="4">
          <v-card>
            <v-img
              :src="card.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="200px"
            >
            </v-img>

            <v-card-actions class="pa-4">
              <v-spacer></v-spacer>
              <v-card-title v-text="card.title"> </v-card-title>
              <v-spacer></v-spacer>
              <span v-text="card.rating" class="px-4 grey--text text--darken-1">
              </span>
              <v-rating
                v-model="rating"
                background-color="white"
                color="yellow accent-4"
                dense
                half-increments
                hover
                size="18"
              ></v-rating>
            </v-card-actions>

            <v-card-actions>
              <v-card-title
                class="primary--text f-600 me-1"
                v-text="card.price"
              >
              </v-card-title>
              <span v-text="card.info" class="px-4 grey--text text--darken-1">
              </span>
            </v-card-actions>
          </v-card>
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
        title: "Risotto ",
        src: "https://images.unsplash.com/photo-1532634922-8fe0b757fb13?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8N3x8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.3,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$5",
        flex: 12,
      },
      {
        title: "Pasta",
        src: "https://images.unsplash.com/photo-1543353071-087092ec393a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.6,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$5",
        flex: 12,
      },
      {
        title: " Gnocchi",
        src: "https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjB8fGZvb2QlMjBhbmQlMjBkcmlua3xlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.1,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$5",
        flex: 12,
      },
      {
        title: "Lasagne",
        src: "https://media.istockphoto.com/photos/food-with-high-content-of-omega3-fats-picture-id1301412050?b=1&k=20&m=1301412050&s=170667a&w=0&h=nViB9ZIwyVRLPD5s123i48XNq_MNUvdBtX3IzAHnqec=",
        rating: 4.6,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$5",
        flex: 12,
      },
      {
        title: "Tiramisù",
        src: "https://images.unsplash.com/photo-1540189549336-e6e99c3679fe?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Zm9vZHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.4,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$5",
        flex: 12,
      },
      {
        title: "Sardine in Saor",
        src: "https://images.unsplash.com/photo-1498837167922-ddd27525d352?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8Zm9vZHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60",
        rating: 4.5,
        info: " • Cofee, set menu • 15 - 20 min ",
        price: "$5",
        flex: 12,
      },
    ],
  }),
};
</script>

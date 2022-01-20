<template>
  <v-container py-15 pd>
    <h1>Browse By Cuisine</h1>
    <v-spacer></v-spacer>
    <br />
    <v-row dense justify="space-around">
      <v-col v-for="card in cards" :key="card.name" cols="12" md="2">
        <div
          class="v-avatar mb-4"
          style="height: 150px; min-width: 150px; width: 150px"
        >
          <v-img :src="card.src"></v-img>
        </div>
        <div>
          <br />
          <a href="/resturant/FoodMenu" class="text-decoration-none">
            <v-text
              style="height: 150px; min-width: 150px; width: 150px align-center"
              v-text="card.name"
            >
            </v-text>
          </a>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    cards: [
      {
        name: "Japanesse",
        src: "https://images.unsplash.com/photo-1543353071-087092ec393a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
      },
      {
        name: "Indian",
        src: "https://images.unsplash.com/photo-1543353071-087092ec393a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
      },

      {
        name: "Italian",
        src: "https://images.unsplash.com/photo-1506368249639-73a05d6f6488?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
      },
      {
        name: "Chinesse",
        src: "https://images.unsplash.com/photo-1612927601601-6638404737ce?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8M3x8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
      },

      {
        name: "Thai Food",
        src: "https://images.unsplash.com/photo-1506368249639-73a05d6f6488?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
      },
      {
        name: "Mexican",
        src: "https://images.unsplash.com/photo-1612927601601-6638404737ce?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8M3x8Zm9vZCUyMGFuZCUyMGRyaW5rfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60",
        flex: 12,
      },
    ],
  }),
};
</script>

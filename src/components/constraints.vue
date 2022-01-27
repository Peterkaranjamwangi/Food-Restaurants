<template>
  <v-card flat color="grey lighten-2">
    <v-card-text>
      <v-container>
        <v-row>
          <v-col xm="6" sm="3" md="3">
            <h3>Categories</h3>
            <v-checkbox
              v-model="ex4"
              label="Fruits"
              value="red"
              hide-details
            ></v-checkbox>

            <v-checkbox
              v-model="ex4"
              label="Vegetables"
              value="Vegetables"
              hide-details
            ></v-checkbox
            ><v-checkbox
              v-model="ex4"
              label="Grains"
              value="Grains"
              hide-details
            ></v-checkbox
            ><v-checkbox
              v-model="ex4"
              label="fish"
              value="fish"
              hide-details
            ></v-checkbox
            ><v-checkbox
              v-model="ex4"
              label="pasta"
              value="pasta"
              hide-details
            ></v-checkbox>
          </v-col>
          <v-col xm="6" sm="3" md="3">
            <h3>Ratings</h3>
            <v-checkbox
              v-model="ex4"
              label="4+"
              value="indigo"
              hide-details
            ></v-checkbox>
            <v-checkbox
              v-model="ex4"
              label="4+"
              value="indigo-2"
              hide-details
            ></v-checkbox
            ><v-checkbox
              v-model="ex4"
              label="4+"
              value="indigo-3"
              hide-details
            ></v-checkbox
            ><v-checkbox
              v-model="ex4"
              label="4+"
              value="indigo-4"
              hide-details
            ></v-checkbox
            ><v-checkbox
              v-model="ex4"
              label="4+"
              value="indigo-5"
              hide-details
            ></v-checkbox>
          </v-col>
          <v-col xm="6" sm="3" md="3">
            <h3>Sort by:</h3>
            <v-radio-group v-model="ex7" column>
              <v-radio label="red" color="red" value="red"></v-radio>
              <v-radio label="Popularity" value="red darken-3"></v-radio>
              <v-radio label="indigo" value="indigo"></v-radio>
              <v-radio label="Popularity" value="indigo darken-3"></v-radio>
              <v-radio label="orange" value="orange"></v-radio>
              <v-radio label="Popularity" value="orange darken-3"></v-radio>
            </v-radio-group>
          </v-col>
          <v-col xm="6" sm="3" md="3">
            <h3>Cost per person</h3>
            <v-range-slider
              v-model="range"
              :max="max"
              :min="min"
              hide-details
              class="align-center"
            >
              <template v-slot:prepend>
                <v-text-field
                  :value="range[0]"
                  class="mt-0 pt-0"
                  hide-details
                  single-line
                  type="number"
                  style="width: 60px"
                  @change="$set(range, 0, $event)"
                ></v-text-field>
              </template>
              <template v-slot:append>
                <v-text-field
                  :value="range[1]"
                  class="mt-0 pt-0"
                  hide-details
                  single-line
                  type="number"
                  style="width: 60px"
                  @change="$set(range, 1, $event)"
                ></v-text-field>
              </template>
            </v-range-slider>
          </v-col>
        </v-row>
      </v-container>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      min: 0,
      max: 100,
      range: [0, 100],
    };
  },
};
</script>

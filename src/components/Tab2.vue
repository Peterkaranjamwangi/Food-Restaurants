<template>
  <v-container fluid>
    <v-row align="center">
      <v-col class="d-flex" cols="6" sm="3">
        <v-select :items="items" label="Date" dense></v-select>
      </v-col>

      <v-col class="d-flex" cols="6" sm="3">
        <v-select :items="items" label="Number Of guests" dense></v-select>
      </v-col>
    </v-row>
    <v-row align="center">
      <v-col class="d-flex" cols="6" sm="3">
        <v-text-field
          placeholder="first name"
          outlined
          label="First Name"
        ></v-text-field>
      </v-col>

      <v-col class="d-flex" cols="6" sm="3">
        <v-text-field
          placeholder="last name"
          label="Last Name"
          outlined
        ></v-text-field>
      </v-col>
    </v-row>
    <v-row align="center">
      <v-col class="d-flex" cols="6" sm="3">
        <v-text-field label="Email" placeholder="email" outlined></v-text-field>
      </v-col>

      <v-col class="d-flex" cols="6" sm="3">
        <v-text-field label="Phone" placeholder="phone" outlined></v-text-field>
      </v-col>
    </v-row>
    <v-row align="center">
      <v-col class="d-flex" cols="6" sm="3">
        <button
          type="button"
          class="v-btn v-btn--is-elevated v-btn--has-bg theme--light v-size--default primary"
        >
          <span class="v-btn__content">Book</span>
        </button>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    items: ["1", "2", "3", "4", "5", "6", "7", "8"],
  }),
};
</script>

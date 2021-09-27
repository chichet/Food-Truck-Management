<template>
  <v-container>
    <v-row class="text-center" align-content="start">

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Home
        </h1>
      </v-col>

      <v-col
        class="mb-4 ml-5"
        cols="12"
      >
      <v-row
        align="center"
        justify="center">
        <v-btn depressed>
            Explore
        </v-btn>
        <v-btn depressed>
           View Order History
        </v-btn>
        <v-btn depressed>
           View Current Information
        </v-btn>
      </v-row>
      </v-col>

      <v-col
        class="mb-4 ml-10"
        cols="12"
      >
          <v-row
        align="center"
        justify="center">
        <v-btn depressed>
            Manage Food Truck
        </v-btn>
        <v-btn depressed>
           View Food Truck History
        </v-btn>
      </v-row>
      </v-col>
      <v-col
        class="mb-8 ml-15"
        cols="12"
      >
          <v-row
        align="center"
        justify="center">
        <v-btn depressed>
            Manage Building and Station
        </v-btn>
        <v-btn depressed>
           Manage Food
        </v-btn>
      </v-row>
      </v-col>
  </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'Main',

    data: () => ({
    }),
  }
</script>

<template>
  <v-container>
    <v-row class="text-center">

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          GT Food Truck
        </h1>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <label for="user">Username:    </label>
        <input v-model="message" name = "user" placeholder="Username">
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
          <label for="password">Password:    </label>
          <input v-model="message" name = "password" placeholder="password">
      </v-col>
    </v-row>
    <v-row
    align="center"
    justify="space-around"
  >
    <v-btn depressed>
      Sign in
    </v-btn>
    <v-btn depressed>
      Register
    </v-btn>
  </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
    }),
  }
</script>

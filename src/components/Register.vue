<template>
  <v-container>
    <v-row class="text-center">

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Register
        </h1>
      </v-col>

      <v-col
        class="mb-4 ml-5"
        cols="12"
      >
      <v-row
        align="center"
        justify="center">
        <label for="user">Username:    </label>
        <input v-model="message" name = "user" placeholder="Username">
        <label for="email">Email:    </label>
        <input v-model="message" name = "email" placeholder="email address">
      </v-row>
      </v-col>

      <v-col
        class="mb-4 ml-10"
        cols="12"
      >
          <v-row
        align="center"
        justify="center">
        <label for="first">First Name:    </label>
          <input v-model="message" name = "first" placeholder="First Name">
        <label for="last">Last Name:    </label>
        <input v-model="message" name = "last" placeholder="Last Name">
      </v-row>
      </v-col>
      <v-col
        class="mb-8 ml-15"
        cols="12"
      >
          <v-row
        align="center"
        justify="center">
        <label for="password">Password:    </label>
          <input v-model="message" name = "password" placeholder="password">
        <label for="confirm">Confirm Password:    </label>
        <input v-model="message" name = "confirm" placeholder="password">
      </v-row>
      </v-col>
      <v-col
        class="mb-8 ml-3"
        cols="12"
      >
          <v-row
        align="center"
        justify="center">
        <label for="balance">Balance:    </label>
          <input v-model="message" name = "balance" placeholder="balance">
          <input type="radio" id="Admin" value="Admin" v-model="picked">
          <label  class = "mr-6" for="Admin">Admin</label>
        <input type="radio" id="Manager" value="manager" v-model="picked">
         <label  class = "mr-6" for="Manager">Manager</label>
        <input type="radio" id="Staff" value="Staff" v-model="picked">
         <label for="Staff">Staff</label>
      </v-row>
      </v-col>
    </v-row>
    <v-row
        align="center"
        justify="center"
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
    name: 'Register',

    data: () => ({
    }),
  }
</script>

<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <label for="user">Username: </label>
    <input v-model="message" name = "user" placeholder="Username">
    <p></p>
    <label for="password">Password: </label>
    <input v-model="message" name = "password" placeholder="Password">
  </div>
   <v-row
    align="center"
    justify="space-around"
  >
    <v-btn depressed>
      Normal
    </v-btn>
    <v-btn
      depressed
      color="primary"
    >
      Primary
    </v-btn>
    <v-btn
      depressed
      color="error"
    >
      Error
    </v-btn>
    <v-btn
      depressed
      disabled
    >
      Disabled
    </v-btn>
  </v-row>
</template>

<script>
export default {
  name: 'LogInPage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.hallo {
  display: flex; /* or inline-flex */
  flex-direction: row
}
</style>

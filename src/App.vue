<template>
  <v-app>
    <v-main>
      <HelloWorld/>
      <Register/>
      <Main/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Register from './components/Register.vue';
import Main from './components/Main.vue';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Register,
    Main,
  },

  data: () => ({
    //
  }),
};
</script>

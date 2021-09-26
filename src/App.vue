<template>
  <v-app>
    <v-main>
      <HelloWorld/>
      <Register/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Register from './components/Register.vue';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Register,
  },

  data: () => ({
    //
  }),
};
</script>

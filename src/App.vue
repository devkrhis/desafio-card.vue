<template>
  <v-app>
    <v-main>
      <cardHome/>
    </v-main>
  </v-app>
</template>

<script>
import cardHome from './components/cardHome';

export default {
  name: 'App',

  components: {
    cardHome,
  },

  data: () => ({
    //
  }),
};
</script>

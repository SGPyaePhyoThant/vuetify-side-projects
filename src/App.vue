<template>
  <v-app>
    <!-- <v-app-bar
      app
      color="white"
      dark
      flat
      extended
      rounded
      floating
      class="indigo"
    >
    </v-app-bar> -->
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>

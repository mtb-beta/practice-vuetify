<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    </v-app-bar>

    <v-main>
      <HelloWorld/>
      <v-alert type="success">これはSuccessです。</v-alert>
      <v-alert type="info">これはInfoです。</v-alert>
      <v-alert type="warning">これはWarningです。</v-alert>
      <v-alert type="error">これはErroです。</v-alert>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>

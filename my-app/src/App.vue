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
      <v-alert 
        border="top"
        color="red lighten-2"
      >
        これはred lighten-2です。
      </v-alert>
      <v-alert 
        border="top"
        color="red lighten-1"
      >
        これはred lighten-1です。
      </v-alert>
      <v-alert 
        border="top"
        color="red"
      >
        これはredです。
      </v-alert>
      <v-alert 
        border="top"
        color="red darken-1"
      >
        これはred darken-1です。
      </v-alert>
      <v-alert 
        border="top"
        color="red darken-2"
      >
        これはred darken-2です。
      </v-alert>
      <v-alert
        border="right"
        color="blue-grey"
      >
        これはblue-greyです。
      </v-alert>
      <v-alert 
        border="bottom"
        color="pink darken-1"
      >
        これはpink darken-1です。
      </v-alert>
      <v-alert 
        border="left"
        type="indigo"
      >
        これはindigoです。
      </v-alert>
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

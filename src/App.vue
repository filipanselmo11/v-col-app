<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <br/><br/>

    <v-main>
      <v-col-component-1></v-col-component-1>
      <br/><br/>
      <v-col-component-2></v-col-component-2>
    </v-main>
  </v-app>
</template>

<script>
import VColComponent1 from './components/VColComponent1.vue';
import VColComponent2 from './components/VColComponent2.vue';
export default {
  name: "App",

  components: {VColComponent1, VColComponent2},

  data: () => ({
    //
  }),
};
</script>

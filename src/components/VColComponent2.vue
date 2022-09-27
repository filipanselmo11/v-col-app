<template>
  <v-container class="red lighten-5">
    <v-row class="mb-6" no-gutters>
      <v-col md="4">
        <v-card class="pa-2" outlined tile> .col-md-4 </v-card>
      </v-col>
      <v-col md="2" offset-md="6">
        <v-card class="pa-2" outlined tile> .col-md-2 .offset-md-6 </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "VColComponent2",
};
</script>

<style>
</style>
<template>
  <v-container class="yellow lighten-5">
    <v-row>
        <v-col sm="9">
            <v-card class="pa-2" outlined tile>Level 1</v-card>
            <v-row no-gutters>
                <v-col cols="2" sm="6">
                    <v-card class="pa-2" outlined style="background: lightgrey;" tile>
                        Level 2
                    </v-card>
                </v-col>
                <v-col cols="2" sm="6">
                    <v-card class="pa-2" outlined style="background: lightgrey;" tile>
                        Level 3
                    </v-card>
                </v-col>
            </v-row>
        </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'VColComponent4',
}
</script>

<style>

</style>
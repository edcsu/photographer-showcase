<template>
  <v-container >
    <v-row class="text-center">
      <v-col class="" cols="12">
        <h1 class="display-3 font-weight-bold mb-3">
          Our Team
        </h1>
      </v-col>
    </v-row>
    <v-row class="text-center">
      <v-col cols="4">
        <v-card>
          <v-img
            :src="require('../assets/logo.svg')"
            class="my-3"
            contain
            height="200"
          />
          <v-card-title>Jonathan Smith</v-card-title>
          <v-card-subtitle>Outdoor Photographer</v-card-subtitle>
          <v-card-actions class="text-center">
            <v-btn icon>
                <v-icon>mdi-twitter</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-instagram</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-youtube</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-facebook</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
      <v-col cols="4">
        <v-card>
          <v-img
            :src="require('../assets/logo.svg')"
            class="my-3"
            contain
            height="200"
          />
          <v-card-title>Jonathan Smith</v-card-title>
          <v-card-subtitle>Managing Director</v-card-subtitle>
          <v-card-actions class="text-center">
            <v-btn icon>
                <v-icon>mdi-twitter</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-instagram</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-youtube</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-facebook</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
      <v-col cols="4">
        <v-card>
          <v-img
            :src="require('../assets/logo.svg')"
            class="my-3"
            contain
            height="200"
          />
          <v-card-title>Jonathan Smith</v-card-title>
          <v-card-subtitle>Outdoor Photographer</v-card-subtitle>
          <v-card-actions class="text-center">
            <v-btn icon>
                <v-icon>mdi-twitter</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-instagram</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-youtube</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-facebook</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'TeamSection',
}
</script>

<style>

</style>
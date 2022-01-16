<template>
  <v-container >
    <v-row class="text-center">
      <v-col class="" cols="12">
        <h1 class="display-3 font-weight-bold mb-3">
          Our Services
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
          <v-card-title>Stock Photography</v-card-title>
          <v-card-text>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Blanditiis delectus, alias vitae facere fugit iste sit voluptatum laboriosam optio aspernatur? 
          </v-card-text>
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
          <v-card-title>Stock Photography</v-card-title>
          <v-card-text>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Blanditiis delectus, alias vitae facere fugit iste sit voluptatum laboriosam optio aspernatur? 
          </v-card-text>
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
          <v-card-title>Stock Photography</v-card-title>
          <v-card-text>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Blanditiis delectus, alias vitae facere fugit iste sit voluptatum laboriosam optio aspernatur? 
          </v-card-text>
        </v-card>
        
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'ServicesSection',
}
</script>

<style>

</style>
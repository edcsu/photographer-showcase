<template>
  <div class="grey-color">
    <v-container>
      <v-row class="">
        <v-col class="" cols="12">
          <h1 class="display-3 font-weight-bold mb-3">
            Our Projects
          </h1>
        </v-col>
      </v-row>
      <v-row class="text-center">
        <v-col cols="4">
          <v-card color="transparent">
            <v-img
              :src="require('../assets/logo.svg')"
              class="my-3"
              contain
              height="200"
            />
            <v-card-title>Outdoor Projects For Fashion Showy</v-card-title>
          </v-card>
          
        </v-col>
        <v-col cols="4">
          <v-card color="transparent">
            <v-card-text>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
              Iure et debitis molestias exercitationem quia ipsam ducimus quis assumenda est modi qui, quam numquam. 
            </v-card-text>
            <v-card-text>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
              Officia perspiciatis eligendi quisquam magni ut consequatur cumque ab
              adipisci atque non consectetur voluptatibus expedita aut et facere praesentium, fuga, quaerat asperiores.  
            </v-card-text>
            <v-btn x-large color="black" class="white--text mb-4">
              Explore More
            </v-btn>
          </v-card>
          
        </v-col>
        <v-col cols="4">
          <v-card color="transparent">
            <v-img
              :src="require('../assets/logo.svg')"
              class="my-3"
              contain
              height="200"
            />
            <v-card-title>Product launch outdoor shoot</v-card-title>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
    name: 'ProjectsSection',
}
</script>

<style>
  .grey-color{
    background-color: #F5F5F5;
  }
</style>
<template>
  <v-container class="my-12 py-12">
    <v-row class="text-center">
      <v-col class="" cols="12">
        <h1 class="display-3 font-weight-bold mb-3">
          Latest Blog Posts
        </h1>
      </v-col>
    </v-row>
    <v-row class="">
      <v-col cols="6">
        <v-card>
          <v-img
            :src="require('../assets/logo.svg')"
            class="my-3"
            contain
            height="200"
          >
            <v-chip
              class="ma-4"
              color="grey lighten-4"
              label
            >
              Trending
            </v-chip>
          </v-img>

          <v-card-subtitle class="pb-0">
             <v-container >
              <v-row class="font-italic">
                <v-col class="" cols="6">
                  <span>29 April, 2020</span>
                </v-col>
                <v-col class="text-right" cols="6">
                  <span>2 min read</span>
                </v-col>
              </v-row>
             </v-container>
          </v-card-subtitle>
          <v-card-title class="mt-n6">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Blanditiis delectus, alias vitae facere fugit iste sit voluptatum laboriosam optio aspernatur? 
          </v-card-title>
          <v-container class="mt-n7" >
              <v-row class="">
                <v-col class="mt-6" cols="6">
                  <span>By Jonathan Smith</span>
                </v-col>
                <v-col class="" cols="6">
                  <v-card-actions>
                    <v-btn
                      outlined
                      color=""
                      x-large
                    >
                      Read More
                    </v-btn>
                  </v-card-actions>
                </v-col>
              </v-row>
             </v-container>
        </v-card>
        
      </v-col>
      <v-col cols="6">
        <v-card>
          <v-img
            :src="require('../assets/logo.svg')"
            class="my-3"
            contain
            height="200"
          >
            <v-chip
              class="ma-4"
              color="grey lighten-4"
              label
            >
              Trending
            </v-chip>
          </v-img>

          <v-card-subtitle class="pb-0">
             <v-container >
              <v-row class="font-italic">
                <v-col class="" cols="6">
                  <span>29 April, 2020</span>
                </v-col>
                <v-col class="text-right" cols="6">
                  <span>2 min read</span>
                </v-col>
              </v-row>
             </v-container>
          </v-card-subtitle>
          <v-card-title class="mt-n6">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Blanditiis delectus, alias vitae facere fugit iste sit voluptatum laboriosam optio aspernatur? 
          </v-card-title>
          <v-container class="mt-n7" >
              <v-row class="">
                <v-col class="mt-6" cols="6">
                  <span>By Jonathan Smith</span>
                </v-col>
                <v-col class="" cols="6">
                  <v-card-actions>
                    <v-btn
                      outlined
                      color=""
                      x-large
                    >
                      Read More
                    </v-btn>
                  </v-card-actions>
                </v-col>
              </v-row>
             </v-container>
        </v-card>
      </v-col>
    </v-row>
    <v-row class="text-center">
      <v-col class="" cols="12">
        <v-btn x-large color="black" class="white--text">
          Read all our Blogs
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'LatestBlogsSection',
}
</script>

<style>

</style>
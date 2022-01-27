<template>
  <v-container class="py-16">
    <v-row class="text-center">
      <v-col cols="4" class="my-16 pt-16">
        <v-row class="text-center">
          <v-col cols="6">
            <v-card>
              <v-card-title>134+</v-card-title>
              <v-card-text>
                Satisified clients
              </v-card-text>
            </v-card>
          </v-col> 
          <v-col cols="6">
            <v-card>
              <v-card-title>1159+</v-card-title>
              <v-card-text>
                Projects done
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
        <v-row class="text-center">
          <v-col cols="6">
            <v-card>
              <v-card-title>10+</v-card-title>
              <v-card-text>
                Projects running
              </v-card-text>
            </v-card>
          </v-col> 
          <v-col cols="6">
            <v-card>
              <v-card-title>33+</v-card-title>
              <v-card-text>
                Coffee cups/ day
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="4">
        <v-card>
          <v-img
            :src="require('../assets/logo.svg')"
            class="my-3"
            contain
            height="400"
          />
        </v-card>
        
      </v-col>
      <v-col cols="4">
        <v-card>
          <v-card-title class="display-1 mb-3">
            Why Hire Me For Your Next Project?
          </v-card-title>
          <v-card-text>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Blanditiis delectus, alias vitae facere fugit iste sit voluptatum laboriosam optio aspernatur? 
          </v-card-text>
          <v-img
            :src="require('../assets/logo.svg')"
            class="my-3"
            contain
            height="100"
          />
        </v-card>
        
      </v-col>
    </v-row>
    <v-row class="text-center">
      <v-col class="" cols="12">
        <v-btn x-large color="black" class="white--text">
          Start Project with Me
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'PleaSection',
}
</script>

<style>

</style>
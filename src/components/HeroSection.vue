<template>
  <div class="grey-color">
    <v-container class="py-16">
      <v-row class="text-center">
        <v-col class="" cols="6">
          <h1 class="display-3 font-weight-bold mb-3">
            hello! I am Alex
          </h1>

          <p class="subheading font-weight-regular">
            Fashion Photographer
          </p>
          <p class="text-left">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
            Eius nulla enim assumenda reprehenderit praesentium cumque quidem, 
            obcaecati temporibus! Consequatur veritatis aliquam mollitia illum 
            ducimus corporis consequuntur reprehenderit dolore officiis. Quasi!   
          </p>
          <h3 class="display-1 mb-3 text-left">
            Alex Martin
          </h3>
          
        </v-col>
        <v-col cols="6">
          <v-img
            :src="require('../assets/logo.svg')"
            class="my-3"
            contain
            height="200"
          />
        </v-col>
      </v-row>
      <v-row class="">
            <v-col class="" cols="12">
              Follow Me@
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
              <v-btn x-large color="black" class="white--text ml-16">
                Hire Me
              </v-btn>
            </v-col>
          </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
    name: 'HeroSection',
}
</script>

<style>
  .grey-color{
    background-color: #F5F5F5;
  }
</style>
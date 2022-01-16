<template>
  <v-app>
    <v-app-bar
      app
      color="#F9F9F9"
      dark
    >
      <v-toolbar-title class="black--text">Fotoz.</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn
        text       
      >
        <span class="black--text">Portfolio</span>
      </v-btn><v-btn
        text       
      >
        <span class="black--text">Blogs</span>
      </v-btn><v-btn
        text       
      >
        <span class="black--text">Contact Me</span>
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        
      >
        <span class="">Download CV</span>
      </v-btn>
    </v-app-bar>

    <v-main>
      <HeroSection />
      <ServicesSection />
      <PleaSection />
    </v-main>
  </v-app>
</template>

<script>
import HeroSection from './components/HeroSection';
import PleaSection from './components/PleaSection';
import ServicesSection from './components/ServicesSection';

export default {
  name: 'App',

  components: {
    HeroSection,
    PleaSection,
    ServicesSection,
  },

  data: () => ({
    //
  }),
};
</script>

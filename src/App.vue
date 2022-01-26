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
      <ProjectsSection />
      <TeamSection />
      <InquirySection />
      <ClientsSection />
      <ReviewSection />
      <LatestBlogsSection />
      <MessageSection />
    </v-main>

    <FooterSection />
  </v-app>
</template>

<script>
import ClientsSection from './components/ClientsSection';
import FooterSection from './components/FooterSection';
import HeroSection from './components/HeroSection';
import InquirySection from './components/InquirySection';
import LatestBlogsSection from './components/LatestBlogsSection';
import MessageSection from './components/MessageSection';
import PleaSection from './components/PleaSection';
import ProjectsSection from './components/ProjectsSection';
import ReviewSection from './components/ReviewSection';
import ServicesSection from './components/ServicesSection';
import TeamSection from './components/TeamSection';

export default {
  name: 'App',

  components: {
    ClientsSection,
    FooterSection,
    HeroSection,
    InquirySection,
    LatestBlogsSection,
    MessageSection,
    PleaSection,
    ProjectsSection,
    ReviewSection,
    ServicesSection,
    TeamSection,
  },

  data: () => ({
    //
  }),
};
</script>

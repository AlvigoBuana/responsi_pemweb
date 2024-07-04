<template>
  <div>
    <Navbar />
    <div id="hero">
      <HeroSection />
    </div>
    <div id="about">
      <AboutSection />
    </div>
    <div id="contact">
      <ContactSection />
    </div>  
    <div id="projects">
      <ProjectsSection />
    </div>
    <div id="footer">
      <footer />
    </div>
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';
import Navbar from '~/components/NavbarSection.vue';
import footer from '~/components/footer.vue';

export default {
  components: {
    HeroSection,
    AboutSection,
    ContactSection,
    ProjectsSection,
    Navbar,
    footer
  }
}
</script>

<style>
body, html {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background: linear-gradient(180deg, #ff4d4d,#dfb237,#FF4D6D );
  color: #FFFFFF; /* Warna teks */
}
</style>

<template>
  <div>
    <HeroSection />
  </div>
  <div>
    <AboutSection />
  </div>
  <div>
    <ContactSection />
  </div>  
  <div>
    <ProjectsSection />
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';

export default {
  components: {
    HeroSection,
    AboutSection,
    ContactSection,
    ProjectsSection
  }
}
</script>./Index.vue
<style>
body, html {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background: linear-gradient(90deg, #ff4d6d, #ffffff, #ff3e3e);
}
</style>

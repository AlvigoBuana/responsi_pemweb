<template>
  <div>
    <HeroSection />
  </div>
  <div>
    <AboutSection />
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

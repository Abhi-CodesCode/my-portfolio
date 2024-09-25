<template>
  <div class="bg-[#111827] min-h-screen">
    <NavBar/>
    <HeroSection/>
    <ServicesSection/>
    <AboutSection/>
    <SkillsSection/>
    <ProjectsSection/>
    <ContactSection/>
    <footerSection/>
  </div>
</template>

<script setup> 
import { defineAsyncComponent } from 'vue';
//Import Components Asynchronously 
const NavBar = defineAsyncComponent(()=>import('@/components/NavBar.vue'));
const HeroSection = defineAsyncComponent(()=>import('@/components/HeroSection.vue'));
const ServicesSection = defineAsyncComponent(()=>import('@/components/ServicesSection.vue'));
const AboutSection = defineAsyncComponent(()=>import('@/components/AboutSection.vue'));
const SkillsSection = defineAsyncComponent(()=>import('@/components/SkillsAndExperiencesSection.vue'));
const ProjectsSection = defineAsyncComponent(()=>import('@/components/ProjectsSection.vue'));
const ContactSection = defineAsyncComponent(()=>import('@/components/ContactSection.vue'));
const footerSection = defineAsyncComponent(()=>import('@/components/footer.vue'));

</script>
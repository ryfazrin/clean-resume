<template>
  <div class="min-h-screen bg-gray-100 flex flex-col items-center py-8">
    <div class="w-full max-w-3xl bg-white rounded-lg shadow-lg p-8">
      <HeaderSection />
      <ContactLinks />
      <ExperienceSection />
      <ProjectsSection />
      <SkillsInterestsSection />
      <EducationSection />
      <CertificationsSection />
    </div>
  </div>
</template>

<script setup>
import HeaderSection from './components/HeaderSection.vue'
import ContactLinks from './components/ContactLinks.vue'
import ExperienceSection from './components/ExperienceSection.vue'
import ProjectsSection from './components/ProjectsSection.vue'
import SkillsInterestsSection from './components/SkillsInterestsSection.vue'
import EducationSection from './components/EducationSection.vue'
import CertificationsSection from './components/CertificationsSection.vue'
</script>
<script setup>
import HeaderSection from './sections/HeaderSection.vue'
import HeroSection from './sections/HeroSection.vue'
import RocketSection from './sections/RocketSection.vue'
import TestimonialsSection from './sections/TestimonialsSection.vue'
import ContactSection from './sections/ContactSection.vue'
</script>

<template>
  <HeaderSection />
  <body class="min-h-screen bg-slate-50 dark:bg-black dark:text-white">
    <main class="max-w-4xl mx-auto">
      <HeroSection />

      <hr class="mx-auto bg-black dark dark:bg-white w-1/2" />
      <RocketSection />

      <hr class="mx-auto bg-black dark dark:bg-white w-1/2" />
      <TestimonialsSection />

      <hr class="mx-auto bg-black dark dark:bg-white w-1/2" />
      <ContactSection />
    </main>
  </body>
</template>

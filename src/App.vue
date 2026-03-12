<script setup>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from "./components/NavBar.vue"
import HeroSection from "./components/HeroSection.vue"
import ServicesSection from "./components/ServicesSection.vue"
import GallerySection from "./components/GallerySection.vue"
import BookingSection from "./components/BookingSection.vue"
import FooterSection from "./components/FooterSection.vue"
import ContactSection from './components/ContactSection.vue'
</script>

<template>
  <div class="bg-gray-50 text-gray-800">

    <NavBar />

    <HeroSection />

    <ServicesSection />

    <GallerySection />

    <BookingSection />

    <ContactSection/>

    <FooterSection />

  </div>
</template>

<style scoped></style>

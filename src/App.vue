<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Servizi from './components/Servizi.vue'
import Testimonials from './components/Testimonials.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <Navbar />
    
    <main class="flex-grow space-y-16 md:space-y-24 py-8">
      <Hero />
      <Servizi />
      <Testimonials />
      <Contact />
    </main>
    
    <Footer class="mt-auto" />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
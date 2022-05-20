<script setup>
import TheWelcome from '@/components/TheWelcome.vue'
import WelcomeBanner from '@/components/WelcomeBanner.vue'
import About from '../components/About.vue';
import Portfolio from '../components/Portfolio.vue';
import Contact from '../components/Contact.vue';
import Footer from '../components/Footer.vue';
import Offer from '../components/Offer.vue';
</script>

<template>
  <main>
    <WelcomeBanner/>
    <Offer/>
    <About/>
    <Portfolio/>
    <Contact/>
    <Footer/>
  </main>
</template>

<style scoped>
main{
  background-color: rgb(220, 220, 228);
}
</style>
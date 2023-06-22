<script setup>
import NavBar from './components/NavBar.vue'
import Carousel from './components/Carousel.vue'
import Footer from './components/Footer.vue';
</script>

<template>
  <header>
    <NavBar />
  </header>
  <main>
    <section class="p-4">
      <Carousel />
    </section>
  </main>
  <footer>
    <Footer />
  </footer>
</template>

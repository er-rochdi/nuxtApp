<template>
    <div>
      <Navbar />
      <main class="min-h-screen">
        <NuxtPage />
      </main>
      <Footer />
    </div>
  </template>
  
  <script setup>
  import Navbar from '~/components/Navbar.vue';
  import Footer from '~/components/Footer.vue';
  </script>
  
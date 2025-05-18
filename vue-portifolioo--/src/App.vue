<template>
  <div class="bg-gray-100 min-h-screen">
    <navbar/>
    <div class="main container mx-auto px-4 py-6">
      <router-view/>
    </div>
  </div> 
   <footer/>
</template>

<script setup>
import Navbar from './components/NavbarComponents.vue'
import Footer from './components/FooterComponents.vue'
</script>

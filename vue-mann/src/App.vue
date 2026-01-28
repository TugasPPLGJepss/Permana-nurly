<script setup>
  import Navbar from '../src/components/Navbar.vue';
</script>

<template>
  <Navbar/>
  <div class="container mt-4">  
    <router-view/>
  </div>
</template>
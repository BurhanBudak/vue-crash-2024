<script setup>
import Hero from './components/Hero.vue';
import HomeCards from './components/HomeCards.vue';
import JobListing from './components/JobListings.vue';
import Navbar from './components/Navbar.vue';


</script>
<template>
  <Navbar />
  <Hero />
  <HomeCards />
  <JobListing :limit="3" :show-button="true"/>
</template>
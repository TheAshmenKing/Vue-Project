<script setup>
  import JobListings from "@/components/JobListings.vue";
  import Hero from "@/components/Hero.vue";
  import HomeCards from "@/components/HomeCards.vue";
</script>

<template>
  <Hero />
  <HomeCards />
  <JobListings :show-button="true" />
</template>

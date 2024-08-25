<script setup>
import Hero from "@/components/Hero.vue";
import HomeCards from "@/components/HomeCards.vue";
import JobLisitngs from "@/components/JobListings.vue";
</script>

<template>
  <Hero title="Test Title" subtitle="Test Subtitle" />
  <HomeCards />
  <JobLisitngs :limit="3" :showButton="true" />
</template>

<script setup>
import Hero from "../components/Hero.vue"
import HomeCards from "../components/HomeCards.vue"
import JobListings from "../components/JobListings.vue"
</script>

<template>
   <Hero title="Find Your Dream Job!" subTitle ="Explore the latest positions at top companies worldwide and start your career anew."></Hero>
   <HomeCards></HomeCards>
   <JobListings :limit="3" :showButton="true" />
</template>
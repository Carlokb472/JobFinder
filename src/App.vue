<script setup>
import Navbar from '@/components/Navbar.vue';
import { RouterView } from 'vue-router';
import Hero from './components/Hero.vue';
import HomeCards from './components/HomeCards.vue';
import JobListings from './components/JobListings.vue';

</script>


<template>
 <Navbar></Navbar>
 <RouterView></RouterView>
</template>

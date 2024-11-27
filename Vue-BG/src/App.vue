<script setup>
  import NavBar from "@/components/NavBar.vue";
  import Hero from "@/components/Hero.vue";
  import HomeCard from "@/components/HomeCard.vue";
  import JobLestings from "@/components/JobLestings.vue";
</script>

<template>
  <NavBar/>
  <Hero title="Test title props"/>
  <HomeCard/>
  <JobLestings :limit="3" :showButton="true"/>
</template>

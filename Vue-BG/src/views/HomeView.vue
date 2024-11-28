<script setup>
import Hero from "@/components/Hero.vue";
import HomeCard from "@/components/HomeCard.vue";
import JobLestings from "@/components/JobLestings.vue";
</script>

<template>
<Hero />
<HomeCard />
<JobLestings :limit="3" :showButton="true" />
</template>

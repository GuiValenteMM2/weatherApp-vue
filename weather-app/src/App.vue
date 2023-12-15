<script setup>
import { RouterView } from 'vue-router';
import Navigation from './components/Navigation.vue';
</script>

<template>
  <div class="flex flex-col min-h-screen bg-weather-primary font-Roboto">
    <Navigation />
    <RouterView />
  </div>
</template>


<template>
  <div id="app" class="flex flex-col min-h-screen">
    <SiteHeader />
    <main class="flex-grow pt-16"> <!-- Adjusted padding here -->
      <router-view />
    </main>
    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue';
import SiteFooter from './components/SiteFooter.vue';

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter,
  },
};
</script>

<style>
/* Add global styles here if needed */
</style>

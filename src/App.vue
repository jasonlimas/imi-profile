<template>
  <div id="app">
    <SiteHeader />
    <main class="min-h-screen">
      <div class="container mx-auto py-20">
        <h1 class="text-center text-3xl mb-4">Welcome to the Company Profile</h1>
        <p class="text-center">This is a temporary content section to visualize the footer.</p>
        <div class="my-40">
          <p class="text-center">Scroll down to see the footer below.</p>
        </div>
      </div>
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

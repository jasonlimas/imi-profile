<template>
    <header class="fixed top-0 w-full bg-white shadow-md">
        <div class="container mx-auto flex items-center justify-between p-4">
            <div class="flex items-center">
            <router-link to="/">
                <img src="@/assets/logo.png" alt="Company Logo" class="h-8 w-auto">
            </router-link>
            </div>
            <nav class="flex-1 flex justify-center space-x-8">
            <router-link to="/solutions" class="text-gray-700 hover:text-gray-900">Solutions</router-link>
            <router-link to="/customers" class="text-gray-700 hover:text-gray-900">Customers</router-link>
            <router-link to="/support" class="text-gray-700 hover:text-gray-900">Support</router-link>
            <router-link to="/contact" class="text-gray-700 hover:text-gray-900">Contact Us</router-link>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name: 'SiteHeader',
};
</script>

<style scoped>
/* Add any additional styles here */
</style>

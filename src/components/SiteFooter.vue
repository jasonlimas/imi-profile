<template>
    <footer class="w-full bg-white text-center py-6">
        <div class="container mx-auto">
        <hr class="border-gray-500 mb-6 mx-auto" style="width: 100%;">
        <p class="text-gray-600 mt-4 text-xs">&copy; {{ currentYear }} PT Intelegensia Mustaka Indonesia. All rights reserved.</p>
        </div>
    </footer>
</template>

<script>
export default {
name: 'SiteFooter',
computed: {
    currentYear() {
    return new Date().getFullYear();
    }
}
};
</script>

<style scoped>
footer {
background-color: #fff;
color: #333;
}
</style>

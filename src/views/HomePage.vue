<template>
    <div class="container mx-auto flex justify-between px-4 md:px-10">
        <div class="w-full md:w-1/5 p-4">
            <img src="@/assets/sample-image.jpg" alt="Sample Image" class="image mb-4">
            <p class="text-center">This is some text below the image on the left.</p>
        </div>
        <div class="w-full md:w-4/5 p-4">
            <img src="@/assets/sample-image.jpg" alt="Sample Image" class="image mb-4">
            <p class="text-center">This is some text below the image on the right.</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomePage',
};
</script>

<style scoped>
.container {
    min-height: calc(100vh - 150px); /* Adjust this based on your header and footer height */
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

@media (min-width: 768px) {
    .container {
    flex-direction: row;
    }
}

.image {
    max-height: 60vh; /* Limits the image height to 60% of the viewport height */
    max-width: 100%; /* Ensures the image doesn't overflow its container */
    object-fit: cover; /* Ensures the image scales properly */
}
</style>

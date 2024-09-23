<script setup>
defineProps({
  title: String,
})
</script>

<template>
    <button class="bg-algo-orange px-8 py-2 rounded-xl text-black font-medium hover:bg-opacity-80 transition duration-200 ease-in-out">
        {{ title }}
    </button>
</template>

<style scoped>

</style>


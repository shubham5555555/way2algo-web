<script setup>
const beg = [
    {
        "title": "Trading Platform",
        "desc": "We offer low fees and fast execution times, so you can make the most of it.",
        "img": "/src/assets/images/beg1.webp"
    },
    {
        "title": "Educational Community",
        "desc": "We offer a range of educational resources to help you learn more about trading.",
        "img": "/src/assets/images/beg2.webp"
    },
    {
        "title": "Market Analysis Tool",
        "desc": "Our platform provides up-to-date news and analysis on the crypto markets.",
        "img": "/src/assets/images/beg3.webp"
    },
]
</script>

<template>
    <section class="px-6 md:px-10 py-10 xl:py-20 3xl:max-w-[85%] mx-auto">
        <div class="text-white text-center font-Inter space-y-5">
            <p class="text-algo-orange text-[16px]">Why Goalgo?</p>
            <h1 class="mx-auto leading-[50px] md:leading-[70px] text-[40px] md:text-[58px] md:w-[90%] xl:text-[64px] xl:w-[60%]">Designed for beginners and <span class="text-algo-orange">experienced traders</span></h1>
            <p class="font-light text-[#8C8C8C]">Our platform is designed to make trading simple, accessible, and profitable for everyone.</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 mt-16 gap-6">
            <div v-for="item in beg" class="p-6 font-Inter border border-white border-opacity-25 rounded-3xl space-y-6">
                <img :src="item.img" alt="" class="w-[90%]">
                <div class="space-y-1">
                    <p class="text-algo-orange text-[19px]">{{ item.title }}</p>
                <p class="text-[#8C8C8C] text-[16px]">{{ item.desc }}</p>
                </div>
            </div>
        </div>
    </section>
</template>




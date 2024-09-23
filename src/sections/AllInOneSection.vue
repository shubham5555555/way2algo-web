<script setup>
const list = [
    {
        "title": "Live & Paper Trade",
        "desc": "Switch between live and simulated trading modes."
    },
    {
        "title": "Live & Paper Trade",
        "desc": "Switch between live and simulated trading modes."
    },
    {
        "title": "Live & Paper Trade",
        "desc": "Switch between live and simulated trading modes."
    },
    {
        "title": "Live & Paper Trade",
        "desc": "Switch between live and simulated trading modes."
    },
    {
        "title": "Live & Paper Trade",
        "desc": "Switch between live and simulated trading modes."
    },
    {
        "title": "Live & Paper Trade",
        "desc": "Switch between live and simulated trading modes."
    },
]
</script>

<template>
    <section class="p-6 md:p-10 flex flex-col xl:flex-row items-center justify-between 3xl:max-w-[85%] mx-auto">
        <div class="w-full xl:w-[50%] font-Inter space-y-14">
            <div class="space-y-6">
                <h1 class=" text-[40px] leading-[50px] md:leading-[70px] md:text-[52px] 2xl:text-[64px]">All-in-one decentralized <span class="text-algo-orange">Algo Trading Platform</span></h1>
                <p class="font-light text-[#8C8C8C] text-[16px]">At <span class="text-algo-orange font-normal">Goalgo Trade</span>, we offer a range of features to help you make the most of your trading experience. Here are just a few of the features we offer:</p>
            </div>
            <ul class="grid grid-cols-1 md:grid-cols-2 gap-8 2xl:gap-12">
                <li v-for="item in list" class="font-Inter flex items-start gap-2 ">
                    <i class="pi pi-check-circle text-algo-orange text-[19px]"></i>
                    <div class="">
                        <p class="text-[19px]">{{ item.title }}</p>
                        <p class="text-[#8C8C8C] text-[16px]">{{ item.desc }}</p>
                    </div>
                </li>
            </ul>
        </div>
        <div class="xl:w-[50%]">
            <img src="../assets/images/AllInOne.png" alt="" class=" md:w-[90%] mx-auto">
        </div>
    </section>
</template>
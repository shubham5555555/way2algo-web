<script setup>
import Button from '../components/Button.vue';
</script>

<template>
    <section class="p-6 md:p-10 3xl:max-w-[85%] mx-auto">
        <div class="flex flex-col items-center justify-center font-Inter space-y-4 xl:space-y-6 bg-white bg-opacity-10 py-8 rounded-2xl">
            <img src="../assets/images/svg/dummyProfile.svg" alt="" class="w-[20%] xl:w-[12%]">
            <h1 class="text-center text-[30px] sm:text-[35px] md:text-[40px] w-[80%] xl:w-[60%] xl:text-[48px] 2xl:text-[56px] leading-[45px] md:leading-[50px] xl:leading-[60px] 2xl:leading-[70px]">Connect, Learn, and Grow - <span class="text-algo-orange">Join Our Thriving Trading Community</span></h1>
            <p class="font-light text-center text-[16px] xl:text-[18px] w-[90%] md:w-[80%]">Join our dynamic trading community to share strategies, gain insights, and enhance your skills. Connect with fellow traders and support your journey to trading success.</p>
            <Button title="Join Now" class="w-[50%] md:w-[30%] xl:w-[20%]"/>
        </div>
    </section>
</template>




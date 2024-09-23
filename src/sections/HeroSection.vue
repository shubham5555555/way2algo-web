<script setup>
import BorderButton from '../components/BorderButton.vue';
</script>

<template>
  <section class="px-6 md:px-10 py-20 xl:py-44 relative 3xl:max-w-[85%] mx-auto">
    <div class="absolute left-16 top-32 hidden xl:block">
      <img src="../assets/images/svg/heroBg1.svg" alt="" />
    </div>
    <div class="absolute top-10 left-[620px] 2xl:left-[720px] hidden xl:block">
        <img src="../assets/images/svg/heroBg3.svg" alt="" />
    </div>

    <div class="text-white font-Inter text-center space-y-6">
      <h1 class="mx-auto text-[50px] md:text-[58px] 2xl:text-[64px] md:w-[65%] xl:w-[42%] leading-[65px]">
        The <span class="text-algo-orange">Future of Trading</span> is Here
      </h1>
      <p class="font-light text-[#8C8C8C] mx-auto md:w-[90%] xl:w-[70%] 2xl:w-[60%]">
        Our algorithmic trading software automates complex strategies,
        delivering speed and precision in every trade. Maximize profits, reduce
        risks, and stay ahead of the market with seamless, data-driven
        execution.
      </p>
    <BorderButton title="Request a Demo" class="w-[70%] md:w-[40%] xl:w-[20%]"/>
    </div>
    <div class="absolute right-16 top-32 hidden xl:block">
      <img src="../assets/images/svg/heroBg2.svg" alt="" />
    </div>
  </section>
</template>

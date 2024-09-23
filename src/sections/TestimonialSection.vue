<script setup></script>

<template>
  <section class="w-full p-6 md:p-10 font-Inter relative 3xl:max-w-[85%] mx-auto">
    <div class="glow-effect hidden xl:block">
    </div>
    <div class="z-10 flex flex-col xl:flex-row items-center justify-between space-y-14 xl:space-y-0  xl:py-20">
      <div class="space-y-6 w-full xl:w-[50%]">
        <p class="text-algo-orange">Testimonials</p>
        <h1 class="text-[54px] md:text-[64px] leading-[55px] md:leading-[65px]">
          Don't take <br />
          <span class="text-algo-orange">our word for it</span>
        </h1>
        <p class="text-[#8C8C8C] text-[16px] md:w-[80%] xl:w-full">
          Our support team is available around the clock to help you with any
          questions or issues you may have.
        </p>
      </div>
      <div class="w-full xl:w-[45%] font-Inter">
        <div class="p-8 rounded-2xl bg-white bg-opacity-10 border border-white border-opacity-25 space-y-5">
          <div class="flex items-start gap-4">
            <img src="../assets/images/svg/dummy.svg" alt="" />
            <div class="">
              <p class="font-[19px]">Sourabh Daharia</p>
              <p class="text-[#8C8C8C] text-[16px]">Invester</p>
            </div>
          </div>
          <p class="font-light text-[18px]">
            “I appreciate the transparent pricing and the powerful features that
            come with it. It's been a seamless experience, and the customer
            support is exceptional!”
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.glow-effect {
  background: radial-gradient(
    circle at top,
    rgba(39, 254, 165, 0.65),
    transparent 40%
  );
  width: 80%;
  right: 150px;
  overflow: hidden;
  position: absolute;
  height: 400px;
  opacity: 50%;
}
</style>

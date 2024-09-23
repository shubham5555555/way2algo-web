<script setup>
import { ref } from "vue";
import Sidebar from "primevue/sidebar";
import Button from "./Button.vue";

const visible = ref(false);
</script>

<template>
  <nav class="text-white px-6 md:px-10 py-4 flex items-center justify-between 3xl:max-w-[85%] mx-auto sticky top-0 z-20 bg-[#102F2A] drop-shadow-md">
   <a href="/" class="w-[45%] md:w-[25%] xl:w-[12%]">
    <img
      src="../assets/images/Logo.png"
      alt=""
      
    />
   </a>
    <div
      class="font-NeueMontreal-Light font-thin hidden xl:flex items-center gap-8 text-[16px] tracking-wider"
    >
      <a href="" class="cursor-pointer">Home</a>
      <a href="" class="cursor-pointer">Services</a>
      <a href="" class="cursor-pointer">Strategy</a>
      <a href="" class="cursor-pointer">About Us</a>
      <a href="" class="cursor-pointer">Blog</a>
      <a href="" class="cursor-pointer">Contact</a>
    </div>
     <Button class="hidden xl:block" title="Login/Signup"/>
    <button class="xl:hidden" @click="visible = true">
      <i class="pi pi-bars text-[25px]"></i>
    </button>
    <Sidebar v-model:visible="visible" position="right">
      <div class="flex flex-col space-y-4 mt-8 text-[19px]">
        <p>Home</p>
        <p>Services</p>
        <p>Strategy</p>
        <p>About Us</p>
        <p>Blog</p>
        <p>Contact</p>
      </div>
      <Button class="mt-10" title="Login/Signup"/>
    </Sidebar>
  </nav>
</template>

<style scoped>

</style>

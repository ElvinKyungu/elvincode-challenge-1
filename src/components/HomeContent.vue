<script setup lang="ts">
  import IconLeft from './icons/IconLeft.vue';
  import ImageHeroDark from '@/assets/hero-image-dark.jpeg'
  import ImageHeroLight from '@/assets/hero-image-light.jpeg'
</script>
<template>
  <main class="pt-28 flex justify-center items-center">
    <div class="relative mt-20 flex justify-center flex-col items-center">
      <div class="flex justify-center gap-3 py-2 font-medium text-sm px-3 rounded-full items-center text-white border-2 border-gray-800">
        <span class="uppercase bg-orange-600 px-2 rounded-full">New</span>
        <span>Design is out now! </span>
      </div>
      <h1 class="text-white text-6xl font-bold text-center my-10">
        Experiece the 
        <span class="text-transparent bg-gradient-to-r from-[#D247BF] to-orange-600 bg-clip-text">
          Shadcn/Vue
        </span><br> 
        landing page 
      </h1>
      <p class="max-w-screen-sm mx-auto text-center text-lg text-[#a8a08b]">
        We're more than just a tool, we're a community of passionate creators. 
        Get access to exclusive resources, tutorials, and support. 
      </p>
      <div class="flex justify-center gap-4 text-white font-semibold mt-7">
        <button class="bg-orange-600 py-2 px-5 rounded-lg flex items-center gap-2">
          Get Started
          <IconLeft/>
        </button>
        <button class="bg-[#342923] py-2 px-5 rounded-lg">Github repository</button>
      </div>
      <div class="mt-10 relative">
        <div
          class="absolute top-2 z-0 lg:-top-8 left-1/2 transform -translate-x-1/2 w-[90%] mx-auto h-24 lg:h-80 bg-orange-600/50 rounded-full blur-3xl"
        >
        </div>
        <img 
          class="
            w-full md:w-[1200px] mx-auto rounded-lg relative 
            leading-none flex items-center border border-[#342923] border-t-2 
            border-t-orange-600/30
          "
          :src="ImageHeroDark" alt=""
        >
      </div>
    </div>
  </main>
</template>
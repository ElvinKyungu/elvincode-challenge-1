<script setup lang="ts">
  import { useDark, useToggle } from '@vueuse/core'
  import Header from '@/components/Header.vue'
  import HomeContent from '@/components/HomeContent.vue';
  const isDark = useDark()
  const toggleDark = useToggle(isDark)  
  
</script>

<template>
  <div class="bg-[#161412] w-full min-h-screen">
    <Header />
    <HomeContent/>
  </div>
</template>

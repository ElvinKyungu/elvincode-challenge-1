<script setup lang="ts">
  import IconDown from './icons/IconDown.vue';
</script>
<template>
  <header class="my-10 mx-80 bg-[#161412] p-4  rounded-md border border-gray-500 flex justify-between">
    <router-link to="/" class="bg-[#c64c0d]">
      <IconDown />
    </router-link>
    <nav>
      <ul class="flex gap-4">
        <li>
          <router-link to="">Features</router-link>
        </li>
        <li>
          <router-link to="">Testimational</router-link>
        </li>
        <li>
          <router-link to="">Team</router-link>
        </li>
        <li>
          <router-link to="">Contact</router-link>
        </li>
        <li>
          <router-link to="">FAQ</router-link>
        </li>
      </ul>
    </nav>
  </header>
</template>
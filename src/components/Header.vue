<script setup lang="ts">
  import IconDown from './icons/IconDown.vue'
  import IconDark from './icons/IconDark.vue'
  import IconLight from './icons/IconLight.vue'
  import IconGithub from './icons/IconGithub.vue'
</script>
<template>
  <header class="shadow-sm shadow-gray-700 my-6 fixed flex items-center justify-between inset-x-0 bg-[#161412] p-2 text-white font-medium rounded-xl border border-gray-800 mx-72">
    <router-link to="/" class="bg-[#c64c0d] p-2 rounded-md">
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
    <div class="icons text-white flex gap-3 items-center">
      <!-- <IconDark /> -->
      <IconLight />
      <IconGithub />
    </div>
  </header>
</template>
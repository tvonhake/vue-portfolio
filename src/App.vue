<script setup lang="ts">
import Home from './components/Home.vue'
</script>

<template>
  <div
    class="font-inter min-h-screen bg-[#373B41] text-[#FDF1DD] flex flex-col justify-between p-4 md:p-10 lg:p-20"
  >
    <!-- Header -->
    <div class="flex justify-between items-start fixed top-0 left-0 p-6">
      <button
        class="bg-[#FDF1DD] text-[#373B41] px-6 py-4 md:px-8 md:py-6 lg:px-10 lg:py-8 rounded-[25px] text-sm md:text-base lg:text-lg"
      >
        HOME
      </button>
    </div>
    <Home />
  </div>
</template>

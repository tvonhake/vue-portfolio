<script setup lang="ts">
defineOptions({
  name: 'HomePage',
})
</script>

<template>
  <!-- Main Content -->
  <div
    class="flex flex-col md:flex-row justify-between mt-8 md:mt-16 px-4 md:px-10 lg:px-20 pt-16 md:pt-20 lg:pt-28 mb-4"
  >
    <div class="flex flex-col md:flex-row items-start w-full px-[10%]">
      <!-- Left Section -->
      <div
        class="font-doto text-6xl md:text-7xl lg:text-8xl font-bold text-[#FDF1DD] space-y-2 w-full mb-10"
      >
        <p>WORK</p>
        <p>ABOUT</p>
        <p>CONTACT</p>
      </div>

      <!-- Right Section -->
      <div class="text-left w-full md:w-3/7 space-y-4 md:space-y-6">
        <h2 class="text-xl md:text-2xl lg:text-3xl font-semibold">Full Stack Software Engineer</h2>
        <p class="text-sm md:text-base lg:text-xl mt-2">
          I specialize in Ruby, React, and cloud infrastructure.<br />
          Let's build something great together.
        </p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <div class="flex items-center justify-center flex-grow">
    <h1
      class="font-inter-tight text-[#56a2ac] w-full text-center text-[18vw] md:text-[18vw] lg:text-[18vw] whitespace-nowrap"
    >
      TREVOR V
    </h1>
  </div>
</template>

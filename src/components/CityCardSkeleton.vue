<template>
  <div class="flex py-6 px-3 bg-gray-800 rounded-md shadow-md">
    <div class="flex flex-col flex-1 gap-2">
      <AnimatedPlaceholder class="max-w-[50%]" />
      <AnimatedPlaceholder class="max-w-[40%]" />
    </div>

    <div class="flex flex-col items-end flex-1 gap-2">
      <AnimatedPlaceholder class="max-w-[50px] w-full" />
      <AnimatedPlaceholder class="max-w-[75px] w-full" />
    </div>
  </div>
</template>

<script setup>
import AnimatedPlaceholder from "./AnimatedPlaceholder.vue";
</script>

<style scoped>
/* Update the background color for the entire component */
div {
  background-color: #121212;
}

/* Update the styles for the animated placeholder content */
.animated-placeholder {
  background-color: #222;
  color: #444;
}

/* Adjust other styles as needed */
</style>
<template>
  <div class="p-6 bg-gray-100 dark:bg-gray-800 rounded-lg shadow text-left">
    <h3 class="text-xl font-semibold mb-2">{{ title }}</h3>
    <p class="mb-4">{{ desc }}</p>
    <a :href="link" target="_blank" class="text-blue-500 hover:underline">View Project →</a>
  </div>
</template>

<script setup>
defineProps({
  title: String,
  desc: String,
  link: String
})
</script>

<template>
  <button 
    @click="toggleDarkMode"
    class="p-2 rounded-full bg-gray-200 dark:bg-gray-800 transition"
  >
    <i class="fas fa-moon dark:hidden"></i>
    <i class="fas fa-sun hidden dark:inline"></i>
  </button>
</template>

<script setup>
const toggleDarkMode = () => {
  document.documentElement.classList.toggle("dark")
}
</script>

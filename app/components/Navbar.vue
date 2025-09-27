<template>
  <header class="fixed top-0 left-0 w-full bg-white/80 dark:bg-gray-900/80 backdrop-blur-md shadow-sm z-50">
    <nav class="max-w-6xl mx-auto flex justify-between items-center py-4 px-6">
      <!-- Logo / Name -->
      <a href="#home" class="text-xl font-bold">Viransh</a>

      <!-- Links -->
      <ul class="flex space-x-6">
        <li><a href="#home" class="hover:text-blue-500">Home</a></li>
        <li><a href="#about" class="hover:text-blue-500">About</a></li>
        <li><a href="#work" class="hover:text-blue-500">Work</a></li>
        <li><a href="#contact" class="hover:text-blue-500">Contact</a></li>
      </ul>

      <!-- Dark Mode Toggle -->
      <DarkModeToggle />
    </nav>
  </header>
</template>

<script setup>
import DarkModeToggle from "./DarkModeToggle.vue"
</script>

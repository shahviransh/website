<template>
  <section class="h-screen flex flex-col justify-center items-center text-center space-y-6">
    <h1 class="text-5xl font-bold">Viransh Shah</h1>
    <p class="text-lg">4th Year Computer Science Student at McMaster University</p>

    <div class="space-x-4">
      <a href="/resume.pdf" target="_blank" class="px-4 py-2 border border-blue-500 text-blue-500 rounded-lg hover:bg-blue-50">
        Resume
      </a>
    </div>

    <SocialLinks />
  </section>
</template>

<script setup>
import SocialLinks from "@/components/SocialLinks.vue"
</script>

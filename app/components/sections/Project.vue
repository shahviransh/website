<template>
  <section class="min-h-screen flex flex-col justify-center items-center text-center p-12">
    <h2 class="text-3xl font-bold mb-6">My Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 max-w-4xl">
      <ProjectCard title="Portfolio Website" desc="A personal site built with Nuxt & Tailwind" link="#" />
      <ProjectCard title="Flask API" desc="REST API for data processing" link="#" />
    </div>
  </section>
</template>

<script setup>
import ProjectCard from "@/components/ProjectCard.vue"
</script>

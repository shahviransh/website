<template>
  <div class="font-sans bg-white dark:bg-gray-900 text-gray-900 dark:text-gray-100">
    <Navbar />
    <main class="scroll-smooth">
      <section id="home"><Home /></section>
      <section id="about"><About /></section>
      <section id="work"><Project /></section>
      <section id="contact"><Contact /></section>
    </main>
  </div>
</template>

<script setup>
import Navbar from "@/components/Navbar.vue"
import Home from "@/components/sections/Home.vue"
import About from "@/components/sections/About.vue"
import Project from "@/components/sections/Project.vue"
import Contact from "@/components/sections/Contact.vue"
</script>

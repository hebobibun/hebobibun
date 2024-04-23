<template>
  <div class="space-y-6">
    <NuxtImg src="/ava.jpg" alt="Muhammad Habibullah"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="webp" />
    <h1 class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100">
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      I'm Habibullah, a software engineer from Indonesia. I specialize in making websites and apps using Golang, JavaScript, Vue &amp; Node.js. Here, I share my fun experiments, cool projects, and thoughts mostly about tech &amp; programming.
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      During the day, I work as a Fullstack Developer at <a href="https://www.linkedin.com/company/magicsoft-asia-system" target="_blank" class="underline">MagicsoftAsia</a>. But in my free time, especially at night and on weekends, I love playing around with different tools and apps that I'm building.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Muhammad Habibullah",
  description:
    "I'm Habibullah, your friendly neighborhood software, product engineer and designer from Indonesia. I specialize in building web applications and sites using Javascript, React, Vue & Node.",
});
</script>

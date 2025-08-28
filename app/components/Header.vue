<script setup lang="ts">

</script>

<template>


  <nav class="fixed w-full top-0 z-50 bg-black/10 backdrop-blur-lg transition-colors duration-300 md:px-10 lg:px-10">
    <div class="container mx-auto flex h-20 items-center justify-between px-4">

      <NuxtLink to="/" class="flex items-center shrink-0">
        <span class="md:flex text-2xl mt-0.5 font-bold text-primary-600 text-white">
               Zarifamo
            </span>
      </NuxtLink>

      <!-- Desktop Menu Links -->
      <div class="hidden md:flex items-center md:gap-8 text-white">


        <NuxtLink to="/"
                  class="text-sm font-medium hover:text-purple-400 transition">Home</NuxtLink>
        <NuxtLink to="/about"
                  class="text-sm font-medium hover:text-purple-400 transition">About</NuxtLink>
        <NuxtLink to="/projects"
                  class="text-sm font-medium hover:text-purple-400 transition">Projects</NuxtLink>
        <NuxtLink to="/contact"
                  class="text-sm font-medium hover:text-purple-400 transition">Contact</NuxtLink>
        <NuxtLink to="/contact"
                  class="cursor-pointer rounded-full border-2 py-2 px-6 border-white bg-white text-purple-900 hover:bg-purple-900 hover:text-white hover:shadow-lg transition duration-300 ease-in-out">
          Contact Now
        </NuxtLink>
      </div>



    </div>
  </nav>



</template>

<style scoped>

</style>
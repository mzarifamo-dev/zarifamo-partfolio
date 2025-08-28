<script setup lang="ts">

</script>

<template>
  <body class="bg-gray-900 text-gray-100 min-h-screen">


  <!-- Hero Section -->
  <section class="min-h-screen flex items-center justify-center pt-16 pb-12 px-6">
    <!-- Gradient Background -->
    <div class="fixed inset-0 bg-gradient-to-br from-gray-900 via-purple-900 to-gray-900 -z-10"></div>

    <!-- Floating Particles -->
    <div class="fixed inset-0 -z-10 opacity-20 overflow-hidden">
      <div class="absolute w-3 h-3 bg-pink-500 rounded-full top-1/4 left-1/4 animate-float"></div>
      <div class="absolute w-2 h-2 bg-purple-500 rounded-full top-1/3 right-1/4 animate-float delay-200"></div>
      <div class="absolute w-4 h-4 bg-indigo-500 rounded-full bottom-1/4 left-1/3 animate-float delay-300"></div>
      <div class="absolute w-3 h-3 bg-pink-600 rounded-full bottom-1/3 right-1/4 animate-float"></div>
    </div>

    <!-- Hero Content -->
    <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center animate-fade-in">
      <!-- Text Content -->
      <div class="space-y-6">
        <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold leading-tight">
           <span class="text-gradient">  About Me</span>
        </h1>

        <div class="h-12 overflow-hidden">
          <h2 class="text-xl md:text-2xl font-mono whitespace-nowrap border-r-4 border-r-pink-500 pr-1 animate-typewriter animate-blink">
            Hi,
          </h2>
        </div>

        <p class="text-gray-300 text-lg max-w-lg">


           I’m Zarifamo — a web designer and coder, and this is my personal portfolio.
          I specialize in building beautiful, functional websites with a focus on clean design and user experience. While I use HTML regularly, I truly enjoy working with Nuxt 4 — it’s where I feel most creative and efficient.
          I got into web design and coding because I love creating things that people can actually use. Seeing an idea come to life on a screen — and knowing I built it — is what keeps me going.
          I especially enjoy working on personal websites, where I can fully express ideas and create something meaningful. My goal is to make people feel happiness and maybe even a little “WOW” when they see my work.
          When I’m not coding, you can usually find me listening to music or reading a good book.
        </p>




      </div>

      <!-- Avatar Image -->
      <div class="relative hidden mt-10 md:block">
        <div class="absolute -inset-4 bg-gradient-to-r from-pink-500 to-purple-600 rounded-2xl opacity-75 blur-xl animate-pulse"></div>
        <div class="relative rounded-2xl overflow-hidden border-4 border-gray-800 transform rotate-1 hover:rotate-0 transition-transform duration-500">
          <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=688&q=80"
               alt="Professional portrait"
               class="w-full h-auto object-cover">
        </div>
      </div>
    </div>
  </section>


  </body>

  <div class="bg-gradient-to-b from-[#121212] to-purple-800 relative  overflow-hidden bg-gray-900">
    <svg
        class="absolute inset-0 -z-10 h-full w-full stroke-white/10 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]"
        aria-hidden="true">
      <defs>
        <pattern id="983e3e4c-de6d-4c3f-8d64-b9761d1534cc" width="200" height="200" x="100%" y="-1"
                 patternUnits="userSpaceOnUse">
          <path d="M.5 200V.5H200" fill="none"></path>
        </pattern>
      </defs>
      <svg x="50%" y="-1" class="overflow-visible fill-gray-800/20">
        <path d="M-200 0h201v201h-201Z M600 0h201v201h-201Z M-400 600h201v201h-201Z M200 800h201v201h-201Z"
              stroke-width="0"></path>
      </svg>
      <rect width="100%" height="100%" stroke-width="0" fill="url(#983e3e4c-de6d-4c3f-8d64-b9761d1534cc)"></rect>
    </svg>
    <div
        class="absolute left-[calc(50%-4rem)] top-10 -z-10 transform-gpu blur-3xl sm:left-[calc(50%-18rem)] lg:left-48 lg:top-[calc(50%-30rem)] xl:left-[calc(50%-24rem)]"
        aria-hidden="true">
      <div class="aspect-[1108/632] w-[69.25rem] bg-gradient-to-r from-[#80caff] to-[#4f46e5] opacity-20"
           style="clip-path:polygon(73.6% 51.7%, 91.7% 11.8%, 100% 46.4%, 97.4% 82.2%, 92.5% 84.9%, 75.7% 64%, 55.3% 47.5%, 46.5% 49.4%, 45% 62.9%, 50.3% 87.2%, 21.3% 64.1%, 0.1% 100%, 5.4% 51.1%, 21.4% 63.9%, 58.9% 0.2%, 73.6% 51.7%)">
      </div>
    </div>
    <div class="mt-[-50px] flex h-screen items-center justify-center">
      <div class="max-w-full flex-shrink-0 px-4 text-center lg:mx-0 lg:max-w-3xl lg:pt-8">
        <h1 class="mt-10 text-5xl font-bold tracking-tight text-white sm:text-6xl">
          This page is about me,
          <span class="text-blue-800">  Zarifamo,</span> and my work as
          <span class="text-blue-800">  a web developer. </span>
        </h1>


      </div>
    </div>
  </div>
  <div class="bg-gradient-to-b from-[#121212] to-purple-800 relative w-full min-h-screen flex items-center ">
    <div class="w-full lg:w-[80%] mx-auto px-4 sm:px-10 lg:px-0 flex flex-col gap-4 pt-10 pb-20 dark:text-white">
      <!-- Title -->
      <div class="flex flex-col gap-2 mb-2 md:mb-4">
        <h2 class="text-4xl font-serif font-semibold">About Me</h2>
        <span class="w-16 h-[4px] bg-blue-800 rounded"></span>
        <span class="w-8 h-[4px] bg-blue-800 rounded"></span>
      </div>

      <h4 class="capitalize text-xl font-semibold">I'm  and i'm
        <span class="text-blue-800">web developer</span>
      </h4>
      <p class="">I’m Zarifamo Munavvarova, a Full Stack Developer who loves creating useful and creative digital solutions. I pay close attention to details and always work to deliver the best results.</p>

      <div class="w-full flex flex-col lg:flex-row gap-6 sm:gap-4 lg:gap-6 justify-between">
        <!-- Col 1 -->
        <div class="w-full flex flex-col items-stretch gap-4">
          <!-- col 1 -->
          <div class="flex flex-col sm:flex-row gap-2 md:gap-6 items-center justify-between font-serif">
            <!-- 1 -->
            <ul class="w-full text-gray-900 dark:text-gray-200">
              <li class="py-2 border-b border-gray-200 dark:border-gray-600"><span class="font-bold">Birthday :</span> 30
                june 2009</li>
              <li class="py-2 border-b border-gray-200 dark:border-gray-600"><span class="font-bold">Website :</span>
                https://website.com</li>
              <li class="py-2 border-b border-gray-200 dark:border-gray-600"><span class="font-bold">Degree :</span> Bsc.
                Computer Science</li>
              <li class="py-2 border-b border-gray-200 dark:border-gray-600"><span class="font-bold">Location :</span>
                Khorog, Tajikistan</li>
            </ul>
            <!-- 2 -->
            <ul class="w-full text-gray-900 dark:text-gray-200 font-serif">
              <li class="py-2 border-b border-gray-200 dark:border-gray-600"><span class="font-bold">Email :</span>
                mzarifamo@gmail.com
              </li>
              <li class="py-2 border-b border-gray-200 dark:border-gray-600"><span class="font-bold">Phone No :</span>
                +992 936003384</li>
              <li class="py-2 border-b border-gray-200 dark:border-gray-600"><span class="font-bold">Employment :</span>
                Remote</li>
              <li class="py-2 border-b border-gray-200 dark:border-gray-600"><span class="font-bold">Freelance :</span>
                Available</li>
            </ul>
          </div>
          <!-- col 2 Buttons -->
          <div class="flex gap-4 justify-center sm:justify-start">
            <a href="/cv.docx" download class="px-4 sm:px-6 py-2 bg-blue-800 rounded-full text-white font-bold">Download CV</a>
          </div>
        </div>
        <!-- col 2 -->
        <div class="w-full flex flex-col gap-2">
          <!-- Progress bar 1 -->
          <div class="flex flex-col gap-2">
            <div class="w-full flex justify-between font-semibold">
              <span>WordPress</span>
              <span>92 %</span>
            </div>
            <!-- Progress bar -->
            <div class="w-full bg-gray-300 rounded-full">
              <div class="w-[92%] h-2 bg-blue-900 rounded-full"></div>
            </div>
          </div>

          <!-- Progress bar 2 -->
          <div class="flex flex-col gap-2">
            <div class="w-full flex justify-between font-semibold">
              <span>HTML/CSS/Javascript</span>
              <span>90 %</span>
            </div>
            <!-- Progress bar -->
            <div class="w-full bg-gray-300 rounded-full">
              <div class="w-[90%] h-2 bg-blue-800 rounded-full"></div>
            </div>
          </div>

          <!-- Progress bar 3 -->
          <div class="flex flex-col gap-2">
            <div class="w-full flex justify-between font-semibold">
              <span>PHP/Laravel</span>
              <span>80 %</span>
            </div>
            <!-- Progress bar -->
            <div class="w-full bg-gray-300 rounded-full">
              <div class="w-[80%] h-2 bg-blue-800 rounded-full"></div>
            </div>
          </div>

          <!-- Progress bar 4 -->
          <div class="flex flex-col gap-2">
            <div class="w-full flex justify-between font-semibold">
              <span>Vue/Nuxt</span>
              <span>100 %</span>
            </div>
            <!-- Progress bar -->
            <div class="w-full bg-gray-300 rounded-full">
              <div class="w-[100%] h-2 bg-blue-800 rounded-full"></div>
            </div>
          </div>

          <!-- Progress bar 4 -->
          <div class="flex flex-col gap-2">
            <div class="w-full flex justify-between font-semibold">
              <span>Nestjs</span>
              <span>70 %</span>
            </div>
            <!-- Progress bar -->
            <div class="w-full bg-gray-300 rounded-full">
              <div class="w-[70%] h-2 bg-blue-800 rounded-full"></div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>



</template>

<style scoped>

</style>
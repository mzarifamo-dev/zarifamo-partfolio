<script setup lang="ts">

</script>

  <template>


    <!-- Middle Section -->
    <section class="w-full flex items-center justify-center min-h-screen overflow-hidden bg-gradient-to-b from-[#121212] to-purple-800">
      <!-- Overlay for better text visibility -->
      <div class="absolute inset-0 bg-black bg-opacity-50"></div>

      <!-- Content -->
      <div class="relative z-10 container mx-auto px-4 text-center text-white">
        <h1 class="mb-6 text-4xl font-bold tracking-tight sm:text-5xl md:text-6xl lg:text-7xl" style="line-height: 1.2">
          Hi, I am<span class="relative whitespace-nowrap text-purple-400 dark:text-purple-400">
        <svg aria-hidden="true" viewBox="0 0 418 42" class="absolute top-2/3 left-0 h-[0.58em] w-full fill-purple-400/70 dark:fill-purple-300/60" preserveAspectRatio="none">
          <path d="M203.371.916c-26.013-2.078-76.686 1.963-124.73 9.946L67.3 12.749C35.421 18.062 18.2 21.766 6.004 25.934 1.244 27.561.828 27.778.874 28.61c.07 1.214.828 1.121 9.595-1.176 9.072-2.377 17.15-3.92 39.246-7.496C123.565 7.986 157.869 4.492 195.942 5.046c7.461.108 19.25 1.696 19.17 2.582-.107 1.183-7.874 4.31-25.75 10.366-21.992 7.45-35.43 12.534-36.701 13.884-2.173 2.308-.202 4.407 4.442 4.734 2.654.187 3.263.157 15.593-.780 35.401-2.686 57.944-3.488 88.365-3.143 46.327.526 75.721 2.23 130.788 7.584 19.787 1.924 20.814 1.98 24.557 1.332l.066-.011c1.201-.203 1.53-1.825.399-2.335-2.911-1.31-4.893-1.604-22.048-3.261-57.509-5.556-87.871-7.36-132.059-7.842-23.239-.254-33.617-.116-50.627.674-11.629.540-42.371 2.494-46.696 2.967-2.359.259 8.133-3.625 26.504-9.810 23.239-7.825 27.934-10.149 28.304-14.005 .417-4.348-3.529-6-16.878-7.066Z"></path>
        </svg>
        <span class="relative"> Zarifamo Munavvarova </span>
      </span>.
        </h1>
        <p class="mx-auto mb-8 max-w-2xl text-lg">
          I am web-designer focused on creating beautiful and user-friendly websites. Explore my work to see how I blend creativity with functionality. Let’s connect and bring your vision to life!
        </p>

        <!-- CTA Button -->
        <div class="flex justify-center items-center mt-8" data-aos="fade-up" data-aos-delay="400">
          <NuxtLink to="/now" rel="noopener noreferrer"
             class="relative flex items-center justify-center px-6 py-3 bg-purple-600 hover:bg-purple-700 text-white text-lg font-semibold rounded-full shadow-lg transform hover:scale-105 transition-transform duration-200">
            <span class="absolute inset-0 rounded-full bg-purple-600 opacity-50 animate-ping"></span>
            <span class="relative z-10 pr-2">Contact ME Now</span>
          </NuxtLink>
        </div>
      </div>

      <!-- Scroll Down Icon -->
      <div class="absolute sm:bottom-14 bottom-10 left-1/2 transform -translate-x-1/2 animate-bounce">
        <NuxtLink to="/about" class="cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7" />
          </svg>
        </NuxtLink>
      </div>
    </section>

    <div class="h-screen bg-gradient-to-b from-[#121212] to-purple-900  dark:text-white">
      <div class="container mx-auto px-4 py-8">
        <h2 class="text-3xl font-semibold text-center text-gray-800 dark:text-gray-200 mb-8">
          Pages that are in my Partfolio
        </h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white dark:bg-gray-800 shadow-lg rounded-lg overflow-hidden">
            <img src="https://islandwebsolutions.ky/wp-content/uploads/2024/01/First-Impressions-web-design.png"
                 alt="Headless UI" class="w-full h-64 object-cover">
            <div class="p-4 md:p-6">
              <h3 class="text-xl font-semibold text-indigo-500 dark:text-indigo-300 mb-2">About</h3>
              <p class="text-gray-700 dark:text-gray-300 mb-4 two-lines">
                This page gives a quick overview of who I am and what I do.
              </p>
              <NuxtLink to="/about"
                 class="inline-block bg-indigo-500 hover:bg-indigo-600 text-white px-4 py-2 rounded-full">Go to page
                </NuxtLink>
            </div>
          </div>

          <div class="bg-white dark:bg-gray-800 shadow-lg rounded-lg overflow-hidden">
            <img src="https://usercontent.one/wp/www.norderbergs.com/wp-content/uploads/2020/09/professional-web-design-social-ink-professional-web-design-png-1000_813.png"
                 alt="Heroicons" class="w-full h-64 object-cover">
            <div class="p-4 md:p-6">
              <h3 class="text-xl font-semibold text-purple-500 dark:text-purple-300 mb-2">Projects</h3>
              <p class="text-gray-700 dark:text-gray-300 mb-4 two-lines">
                This page is about my projects and creative work.</p>
              <NuxtLink to="/projects"
                 class="inline-block bg-purple-500 hover:bg-purple-600 text-white px-4 py-2 rounded-full">Go to page
                </NuxtLink>
            </div>
          </div>

          <div class="bg-white dark:bg-gray-800 shadow-lg rounded-lg overflow-hidden">
            <img src="https://www.pngmart.com/files/22/Web-Designing-Transparent-PNG.png"
                 alt="Hero Patterns" class="w-full h-64 object-cover">
            <div class="p-4 md:p-6">
              <h3 class="text-xl font-semibold text-cyan-500 dark:text-cyan-300 mb-2">Contact</h3>
              <p class="text-gray-700 dark:text-gray-300 mb-4 two-lines">This page is about where
                you can get in touch
                with me.</p>
              <NuxtLink to="/contact"
                 class="inline-block bg-cyan-500 hover:bg-cyan-600 text-white px-4 py-2 rounded-full">Go to page
                </NuxtLink>
            </div>
          </div>

          <!-- Add more items as needed, following the same structure -->

        </div>
      </div>
    </div>
    <section class="bg-gradient-to-b from-[#121212] to-purple-800 py-12 sm:py-16 lg:py-20 xl:py-24">
      <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="text-center">
          <p class="text-sm font-bold uppercase tracking-widest text-white">Explore</p>
          <h2 class="mt-6 text-3xl font-bold tracking-tight text-white sm:text-4xl lg:text-5xl">My Portfolio in 4 Highlights
          </h2>
          <p class="mx-auto mt-6 max-w-2xl text-lg font-normal text-white lg:text-xl lg:leading-8">
            A quick look at who I am, what I do, and how we can work together.
          </p>
        </div>
        <ul class="mx-auto mt-12 grid max-w-md grid-cols-1 gap-10 sm:mt-16 lg:mt-20 lg:max-w-5xl lg:grid-cols-4">
          <li class="flex-start group relative flex lg:flex-col">
                <span
                    class="absolute left-[18px] top-14 h-[calc(100%_-_32px)] w-px bg-gray-300 lg:right-0 lg:left-auto lg:top-[18px] lg:h-px lg:w-[calc(100%_-_72px)]"
                    aria-hidden="true"></span>
            <div
                class="inline-flex h-10 w-10 shrink-0 items-center justify-center rounded-xl border border-gray-300 bg-gray-50 transition-all duration-200 group-hover:border-gray-900 group-hover:bg-gray-900">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" xmlns="http://www.w3.org/2000/svg"
                   class="h-5 w-5 text-gray-600 group-hover:text-white">
                <path
                    d="M21 12C21 13.6569 16.9706 15 12 15C7.02944 15 3 13.6569 3 12M21 5C21 6.65685 16.9706 8 12 8C7.02944 8 3 6.65685 3 5M21 5C21 3.34315 16.9706 2 12 2C7.02944 2 3 3.34315 3 5M21 5V19C21 20.6569 16.9706 22 12 22C7.02944 22 3 20.6569 3 19V5"
                    stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
              </svg>
            </div>
            <div class="ml-6 lg:ml-0 lg:mt-10">
              <h3
                  class="text-xl font-bold text-black before:mb-2 before:block before:font-mono before:text-sm before:text-gray-500">
                My Journey in IT and Creative Projects
              </h3>
              <h4 class="mt-2 text-base text-white">Tools like HTML, CSS, JS, Nuxt4, Figma, CapCut</h4>
            </div>
          </li>
          <li class="flex-start group relative flex lg:flex-col">
                <span
                    class="absolute left-[18px] top-14 h-[calc(100%_-_32px)] w-px bg-gray-300 lg:right-0 lg:left-auto lg:top-[18px] lg:h-px lg:w-[calc(100%_-_72px)]"
                    aria-hidden="true"></span>
            <div
                class="inline-flex h-10 w-10 shrink-0 items-center justify-center rounded-xl border border-gray-300 bg-gray-50 transition-all duration-200 group-hover:border-gray-900 group-hover:bg-gray-900">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" xmlns="http://www.w3.org/2000/svg"
                   class="h-5 w-5 text-gray-600 group-hover:text-white">
                <path
                    d="M2 3L2 21M22 3V21M11.8 20H12.2C13.8802 20 14.7202 20 15.362 19.673C15.9265 19.3854 16.3854 18.9265 16.673 18.362C17 17.7202 17 16.8802 17 15.2V8.8C17 7.11984 17 6.27976 16.673 5.63803C16.3854 5.07354 15.9265 4.6146 15.362 4.32698C14.7202 4 13.8802 4 12.2 4H11.8C10.1198 4 9.27976 4 8.63803 4.32698C8.07354 4.6146 7.6146 5.07354 7.32698 5.63803C7 6.27976 7 7.11984 7 8.8V15.2C7 16.8802 7 17.7202 7.32698 18.362C7.6146 18.9265 8.07354 19.3854 8.63803 19.673C9.27976 20 10.1198 20 11.8 20Z"
                    stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
              </svg>
            </div>
            <div class="ml-6 lg:ml-0 lg:mt-10">
              <h3
                  class="text-xl font-bold text-black before:mb-2 before:block before:font-mono before:text-sm before:text-gray-500">
                Get to Know My Skills and Projects
              </h3>
              <h4 class="mt-2 text-base text-white">Projects – Websites and creative work I’ve built</h4>
            </div>
          </li>
          <li class="flex-start group relative flex lg:flex-col">
                <span
                    class="absolute left-[18px] top-14 h-[calc(100%_-_32px)] w-px bg-white lg:right-0 lg:left-auto lg:top-[18px] lg:h-px lg:w-[calc(100%_-_72px)]"
                    aria-hidden="true"></span>
            <div
                class="inline-flex h-10 w-10 shrink-0 items-center justify-center rounded-xl border border-gray-300 bg-gray-50 transition-all duration-200 group-hover:border-gray-900 group-hover:bg-gray-900">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" xmlns="http://www.w3.org/2000/svg"
                   class="h-5 w-5 text-gray-600 group-hover:text-white">
                <path
                    d="M22 12C22 17.5228 17.5228 22 12 22M22 12C22 6.47715 17.5228 2 12 2M22 12C22 9.79086 17.5228 8 12 8C6.47715 8 2 9.79086 2 12M22 12C22 14.2091 17.5228 16 12 16C6.47715 16 2 14.2091 2 12M12 22C6.47715 22 2 17.5228 2 12M12 22C14.2091 22 16 17.5228 16 12C16 6.47715 14.2091 2 12 2M12 22C9.79086 22 8 17.5228 8 12C8 6.47715 9.79086 2 12 2M2 12C2 6.47715 6.47715 2 12 2"
                    stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
              </svg>
            </div>
            <div class="ml-6 lg:ml-0 lg:mt-10">
              <h3
                  class="text-xl font-bold text-black before:mb-2 before:block before:font-mono before:text-sm before:text-gray-500">
                Explore My
                Portfolio
              </h3>
              <h4 class="mt-2 text-base text-white">About Me – My journey in tech and what I’ve learned</h4>
            </div>
          </li>
          <li class="flex-start group relative flex lg:flex-col">
            <div
                class="inline-flex h-10 w-10 shrink-0 items-center justify-center rounded-xl border border-gray-300 bg-gray-50 transition-all duration-200 group-hover:border-gray-900 group-hover:bg-gray-900">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" xmlns="http://www.w3.org/2000/svg"
                   class="h-5 w-5 text-gray-600 group-hover:text-white">
                <path
                    d="M5.50049 10.5L2.00049 7.9999L3.07849 6.92193C3.964 6.03644 4.40676 5.5937 4.9307 5.31387C5.39454 5.06614 5.90267 4.91229 6.42603 4.86114C7.01719 4.80336 7.63117 4.92617 8.85913 5.17177L10.5 5.49997M18.4999 13.5L18.8284 15.1408C19.0742 16.3689 19.1971 16.983 19.1394 17.5743C19.0883 18.0977 18.9344 18.6059 18.6867 19.0699C18.4068 19.5939 17.964 20.0367 17.0783 20.9224L16.0007 22L13.5007 18.5M7 16.9998L8.99985 15M17.0024 8.99951C17.0024 10.1041 16.107 10.9995 15.0024 10.9995C13.8979 10.9995 13.0024 10.1041 13.0024 8.99951C13.0024 7.89494 13.8979 6.99951 15.0024 6.99951C16.107 6.99951 17.0024 7.89494 17.0024 8.99951ZM17.1991 2H16.6503C15.6718 2 15.1826 2 14.7223 2.11053C14.3141 2.20853 13.9239 2.37016 13.566 2.5895C13.1623 2.83689 12.8164 3.18282 12.1246 3.87469L6.99969 9C5.90927 10.0905 5.36406 10.6358 5.07261 11.2239C4.5181 12.343 4.51812 13.6569 5.07268 14.776C5.36415 15.3642 5.90938 15.9094 6.99984 16.9998V16.9998C8.09038 18.0904 8.63565 18.6357 9.22386 18.9271C10.343 19.4817 11.6569 19.4817 12.7761 18.9271C13.3643 18.6356 13.9095 18.0903 15 16.9997L20.1248 11.8745C20.8165 11.1827 21.1624 10.8368 21.4098 10.4331C21.6291 10.0753 21.7907 9.6851 21.8886 9.27697C21.9991 8.81664 21.9991 8.32749 21.9991 7.34918V6.8C21.9991 5.11984 21.9991 4.27976 21.6722 3.63803C21.3845 3.07354 20.9256 2.6146 20.3611 2.32698C19.7194 2 18.8793 2 17.1991 2Z"
                    stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
              </svg>
            </div>
            <div class="ml-6 lg:ml-0 lg:mt-10">
              <h3
                  class="text-xl font-bold text before:mb-2 before:block before:font-mono before:text-sm before:text-gray-500">
                My Journey in IT and Creative Projects
              </h3>
              <h4 class="mt-2 text-base text-white">Contact – Let’s connect and work togethe</h4>
            </div>
          </li>
        </ul>
      </div>
    </section>
  </template>


<style scoped>

</style>
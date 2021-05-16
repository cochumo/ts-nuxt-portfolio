<template>
  <footer class="bg-white dark:bg-gray-800">
    <div class="container px-6 py-4 mx-auto">
      <div class="lg:flex">
        <div class="w-full -mx-6 lg:w-2/5">
          <div class="px-6">
            <div>
              <nuxt-link
                to="/"
                class="text-xl font-bold text-gray-800 dark:text-white hover:text-gray-700 dark:hover:text-gray-300"
              >
                IGAMOTO.COM
              </nuxt-link>
            </div>

            <p class="max-w-md mt-2 text-gray-500 dark:text-gray-400">
              Welcome to my portfolio site!<br />I'm a front-end engineer.
            </p>

            <div class="flex mt-4 -mx-2">
              <a
                href="https://github.com/cochumo/"
                target="_blank"
                class="mx-2 text-gray-700 dark:text-gray-200 hover:text-gray-600 dark:hover:text-gray-400"
                aria-label="GitHub"
              >
                <svg class="w-4 h-4 fill-current" viewBox="0 0 512 512">
                  <path
                    d="M256 32C132.3 32 32 134.9 32 261.7c0 101.5 64.2 187.5 153.2 217.9 1.4.3 2.6.4 3.8.4 8.3 0 11.5-6.1 11.5-11.4 0-5.5-.2-19.9-.3-39.1-8.4 1.9-15.9 2.7-22.6 2.7-43.1 0-52.9-33.5-52.9-33.5-10.2-26.5-24.9-33.6-24.9-33.6-19.5-13.7-.1-14.1 1.4-14.1h.1c22.5 2 34.3 23.8 34.3 23.8 11.2 19.6 26.2 25.1 39.6 25.1 10.5 0 20-3.4 25.6-6 2-14.8 7.8-24.9 14.2-30.7-49.7-5.8-102-25.5-102-113.5 0-25.1 8.7-45.6 23-61.6-2.3-5.8-10-29.2 2.2-60.8 0 0 1.6-.5 5-.5 8.1 0 26.4 3.1 56.6 24.1 17.9-5.1 37-7.6 56.1-7.7 19 .1 38.2 2.6 56.1 7.7 30.2-21 48.5-24.1 56.6-24.1 3.4 0 5 .5 5 .5 12.2 31.6 4.5 55 2.2 60.8 14.3 16.1 23 36.6 23 61.6 0 88.2-52.4 107.6-102.3 113.3 8 7.1 15.2 21.1 15.2 42.5 0 30.7-.3 55.5-.3 63 0 5.4 3.1 11.5 11.4 11.5 1.2 0 2.6-.1 4-.4C415.9 449.2 480 363.1 480 261.7 480 134.9 379.7 32 256 32z"
                  />
                </svg>
              </a>

              <a
                href="https://twitter.com/cochumo_1128/"
                target="_blank"
                class="mx-2 text-gray-700 dark:text-gray-200 hover:text-gray-600 dark:hover:text-gray-400"
                aria-label="Twitter"
              >
                <svg class="w-4 h-4 fill-current" viewBox="0 0 512 512">
                  <path
                    d="M496,109.5a201.8,201.8,0,0,1-56.55,15.3,97.51,97.51,0,0,0,43.33-53.6,197.74,197.74,0,0,1-62.56,23.5A99.14,99.14,0,0,0,348.31,64c-54.42,0-98.46,43.4-98.46,96.9a93.21,93.21,0,0,0,2.54,22.1,280.7,280.7,0,0,1-203-101.3A95.69,95.69,0,0,0,36,130.4C36,164,53.53,193.7,80,211.1A97.5,97.5,0,0,1,35.22,199v1.2c0,47,34,86.1,79,95a100.76,100.76,0,0,1-25.94,3.4,94.38,94.38,0,0,1-18.51-1.8c12.51,38.5,48.92,66.5,92.05,67.3A199.59,199.59,0,0,1,39.5,405.6,203,203,0,0,1,16,404.2,278.68,278.68,0,0,0,166.74,448c181.36,0,280.44-147.7,280.44-275.8,0-4.2-.11-8.4-.31-12.5A198.48,198.48,0,0,0,496,109.5Z"
                  />
                </svg>
              </a>
            </div>
          </div>
        </div>

        <!-- <div class="mt-6 lg:mt-0 lg:flex-1">
          <div class="grid grid-cols-2 gap-6 sm:grid-cols-3 md:grid-cols-4">
            <div>
              <h3 class="text-gray-700 uppercase dark:text-white">About</h3>
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >Company</a
              >
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >community</a
              >
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >Careers</a
              >
            </div>

            <div>
              <h3 class="text-gray-700 uppercase dark:text-white">Blog</h3>
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >Tec</a
              >
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >Music</a
              >
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >Videos</a
              >
            </div>

            <div>
              <h3 class="text-gray-700 uppercase dark:text-white">Products</h3>
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >Mega cloud</a
              >
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >Aperion UI</a
              >
              <a
                href="#"
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >Meraki UI</a
              >
            </div>

            <div>
              <h3 class="text-gray-700 uppercase dark:text-white">Contact</h3>
              <span
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >+1 526 654 8965</span
              >
              <span
                class="block mt-2 text-sm text-gray-600 dark:text-gray-400 hover:underline"
                >example@email.com</span
              >
            </div>
          </div>
        </div> -->
      </div>
    </div>
    <div>
      <hr class="h-px mt-2 mb-6 bg-gray-300 border-none dark:bg-gray-700" />

      <div>
        <p class="text-center text-gray-800 dark:text-white mb-2">
          © IGAMOTO.COM {{ new Date().getFullYear() }} - All rights reserved
        </p>
      </div>
    </div>
  </footer>
</template>

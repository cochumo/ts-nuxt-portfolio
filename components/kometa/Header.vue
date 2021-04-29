<template>
  <header class="bg-white dark:bg-gray-800">
    <nav class="border-b dark:border-gray-700">
      <div
        class="container px-6 py-4 mx-auto md:flex md:justify-between md:items-center"
      >
        <div class="flex items-center justify-between">
          <div>
            <a
              class="text-xl font-bold text-gray-800 dark:text-white md:text-2xl hover:text-gray-700 dark:hover:text-gray-300"
              href="#"
              >IGAMOTO.COM</a
            >
          </div>

          <!-- Mobile menu button -->
          <div class="md:hidden">
            <button
              type="button"
              class="text-gray-500 dark:text-gray-200 hover:text-gray-600 dark:hover:text-gray-400 focus:outline-none focus:text-gray-600 dark:focus:text-gray-400"
              aria-label="Toggle menu"
            >
              <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                <path
                  d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                ></path>
              </svg>
            </button>
          </div>
        </div>

        <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
        <!-- <div class="items-center md:flex">
          <div
            class="flex flex-col mt-4 space-y-8 md:flex-row md:items-center md:mt-0 md:space-y-0 md:space-x-16"
          >
            <a
              class="block font-medium text-gray-700 dark:text-gray-200 hover:text-gray-900 dark:hover:text-gray-400 hover:underline"
              href="#"
              >glasses Search</a
            >
            <a
              class="block font-medium text-gray-700 dark:text-gray-200 hover:text-gray-900 dark:hover:text-gray-400 hover:underline"
              href="#"
              >How it works!</a
            >
            <a
              class="block font-medium text-gray-700 dark:text-gray-200 hover:text-gray-900 dark:hover:text-gray-400 hover:underline"
              href="#"
              >Why us?</a
            >
            <a
              class="block font-medium text-gray-700 dark:text-gray-200 hover:text-gray-900 dark:hover:text-gray-400 hover:underline"
              href="#"
              >Contact</a
            >

            <button
              class="flex items-center px-5 py-2 text-sm font-medium tracking-wide text-center text-white capitalize transition-colors duration-200 transform bg-gray-700 rounded-md hover:bg-gray-600 focus:outline-none focus:bg-gray-600"
            >
              Get in touch
            </button>
          </div>
        </div> -->
      </div>
    </nav>
  </header>
</template>

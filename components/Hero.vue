<script lang="ts" setup></script>

<template>
  <div>
    <section
      class="bg-cover bg-center bg-no-repeat bg-[url('https://th.bing.com/th/id/OIG3..wMqdnJRqiUUcQKSJGwF?pid=ImgGn')] bg-gray-700 bg-blend-multiply"
    >
      <div class="px-4 mx-auto max-w-screen-xl text-center py-36 pb-24 lg:py-56">
        <h1
          class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-white md:text-5xl lg:text-6xl"
        >
          Belajar Teknologi dengan Mudah dan Menyenangkan
        </h1>
        <p
          class="mb-8 text-lg font-normal text-gray-300 lg:text-xl sm:px-16 lg:px-48"
        >
          Temukan berbagai artikel, tutorial, dan tips seputar teknologi yang
          bisa membantu Anda meningkatkan keterampilan, pengetahuan, dan karier
          Anda.
        </p>
        <div
          class="flex flex-col space-y-4 sm:flex-row sm:justify-center sm:space-y-0"
        >
          <NuxtLink
            to="/article"
            class="inline-flex justify-center items-center py-3 px-5 text-base font-medium text-center text-white rounded-lg bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900"
          >
            Lihat Artikel Terbaru
            <svg
              class="w-3.5 h-3.5 ms-2 rtl:rotate-180"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 14 10"
            >
              <path
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M1 5h12m0 0L9 1m4 4L9 9"
              />
            </svg>
          </NuxtLink>
        </div>
      </div>
    </section>
  </div>
</template>

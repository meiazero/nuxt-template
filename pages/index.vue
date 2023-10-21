<script setup lang="ts">
import Credits from '~/components/Credits.vue'

useHead({
  title: 'Nuxt Template',
  meta: [
    {
      name: 'description',
      content: 'Template Nuxt with tailwindcss and shadcn-ui',
    },
  ],
})
</script>

<template>
  <section class="w-full h-screen py-12 md:py-24 lg:py-32 xl:py-48 bg-black">
    <div class="container space-y-8 flex flex-col justify-center text-center">
      <h1
        class="text-3xl tracking-tighter font-extrabold sm:text-5xl xl:text-6xl/none bg-clip-text text-transparent bg-gradient-to-l from-emerald-600 to-white"
      >
        Welcome to Nuxt Template
      </h1>
      <p
        class="max-w-[550px] text-emerald-200 md:text-xl dark:text-zinc-100 mx-auto"
      >
        This template have installed: Nuxt, Vue 3, Typescript, Tailwind CSS and
        shadcn-ui.
      </p>
      <Credits />
    </div>
  </section>
</template>

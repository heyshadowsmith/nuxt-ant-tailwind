<template>
  <div class="h-screen flex justify-center items-center text-center">
    <div>
      <Logo class="w-48 mx-auto mb-6" />
      <h1 class="text-3xl font-medium mb-3">
        Nuxt Ant Tailwind
      </h1>
      <h2 class="w-2/3 mx-auto mb-6">
        Nuxt Ant Tailwind is an experimental Nuxt project that uses Ant Design components for structure and Tailwindcss for style.
      </h2>
      <a-button href="https://nuxtjs.org/" target="_blank">
        Nuxt Docs
      </a-button>
      <a-button href="https://www.antdv.com/docs/vue/introduce/" target="_blank">
        Ant Design Vue Docs
      </a-button>
      <a-button href="https://tailwindcss.com/" target="_blank">
        Tailwindcss Docs
      </a-button>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo'

export default {
  components: {
    Logo
  }
}
</script>

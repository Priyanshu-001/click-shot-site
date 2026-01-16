<script setup>
useHead({
  meta: [
    { name: 'viewport', content: 'width=device-width, initial-scale=1' }
  ],
  link: [
    { rel: 'icon', href: '/favicon.ico' }
  ],
  htmlAttrs: {
    lang: 'en'
  }
})

const title = 'ClickShot'
const description = 'Capture key movements without interrupting your study'

useSeoMeta({
  title,
  description,
  ogTitle: title,
  ogDescription: description,
  ogImage: 'card.png',
  twitterImage: 'card.png',
  twitterCard: 'summary_large_image'
})
</script>

<template>
  <UApp>
    <UHeader>
      <template #left>
<NuxtLink
  to="/"
  class="flex items-center gap-2 font-semibold tracking-tight"
>
  <AppLogo class="h-10 w-auto" />
  <span class="text-lg">
    <span class="text-gray-900 dark:text-gray-100">Click</span
    ><span class="text-primary">Shot</span>
  </span>
</NuxtLink>



      </template>

      <template #right>
        <UColorModeButton />
      </template>
    </UHeader>

    <UMain>
      <NuxtPage />
    </UMain>

    <USeparator icon="heroicons-puzzle-piece" />

    <UFooter>
      <template #left>
        <p class="text-sm text-muted">
          Will add contact here
        </p>
      </template>

      <template #right>
        <UButton
          to="https://github.com/nuxt-ui-templates/starter"
          target="_blank"
          icon="i-simple-icons-github"
          aria-label="GitHub"
          color="neutral"
          variant="ghost"
        />
      </template>
    </UFooter>
  </UApp>
</template>

<script setup>
import InstallHelp from './components/InstallHelp.vue'

   const route = useRoute()
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

const overlay = useOverlay()
const modal = overlay.create(InstallHelp)

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

const showInstallHelp = ref(false)

onMounted(() => {
 
  if (route.query.atInstall) {
    console.log("Opening")
     modal.open()
    // showInstallHelp.value = true
    // router.replace({ query: {} }) // remove param
  }
})

</script>

<template>
  <UApp>
   <InstallHelp :open="showInstallHelp" />
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
        <UButton icon="i-heroicons-light-bulb"  label="Get started" @click="()=>modal.open()"/>

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
        <a
            href="mailto:clickshotcontact@gmail.com"
            class="underline hover:opacity-80"
          >
            clickshotcontact@gmail.com
          </a>
        </p>
      </template>

      <template #right>
        <UButton
          to="https://github.com/Priyanshu-001/click-shot"
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

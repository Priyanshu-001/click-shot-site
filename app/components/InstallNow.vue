<template>
  <section class="border-t border-gray-200 dark:border-gray-800">
    <UContainer class="py-28 text-center">
      <!-- Heading -->
      <h2 class="text-3xl md:text-4xl font-bold">
        Install ClickShot
      </h2>

      <p class="mt-4 text-gray-500 dark:text-gray-400">
        Get started in seconds. No signup required.
      </p>

      <!-- Stores -->
      <div class="mt-14 flex justify-center gap-12">
        <button class="group flex flex-col items-center gap-3">
          <UIcon
            name="i-logos-chrome"
            class="w-12 h-12 transition-transform group-hover:scale-110"
          />
          <span class="text-xs text-gray-500 dark:text-gray-400">
            Chrome Store
          </span>
        </button>

        <button class="group flex flex-col items-center gap-3">
          <UIcon
            name="i-logos-firefox"
            class="w-12 h-12 transition-transform group-hover:scale-110"
          />
          <span class="text-xs text-gray-500 dark:text-gray-400">
            Firefox Add-ons
          </span>
        </button>

        <button class="group flex flex-col items-center gap-3">
          <UIcon
            name="i-logos-microsoft-edge"
            class="w-12 h-12 transition-transform group-hover:scale-110"
          />
          <span class="text-xs text-gray-500 dark:text-gray-400">
            Edge Store
          </span>
        </button>
      </div>

      <!-- Divider -->
      <div class="my-12 flex items-center gap-4 max-w-md mx-auto">
        <div class="flex-1 h-px bg-gray-200 dark:bg-gray-800" />
        <span class="text-xs text-gray-400">or</span>
        <div class="flex-1 h-px bg-gray-200 dark:bg-gray-800" />
      </div>

      <!-- ZIP CTA -->
      <UButton size="xl" variant="solid">
        <UIcon name="i-heroicons-arrow-down-tray" class="w-5 h-5 mr-2" />
        Download ZIP
      </UButton>

      
    </UContainer>
  </section>
</template>

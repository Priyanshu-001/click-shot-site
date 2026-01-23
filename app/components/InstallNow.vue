<template>
  <section class="border-t border-gray-200 dark:border-gray-800" id="installNow">
    <UContainer class="py-28 text-center" >
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
            Chrome Store [Comming soon]
          </span>
        </button>

        <!-- <button class="group flex flex-col items-center gap-3">
          <UIcon
            name="i-logos-firefox"
            class="w-12 h-12 transition-transform group-hover:scale-110"
          />
          <span class="text-xs text-gray-500 dark:text-gray-400">
            Firefox Add-ons
          </span>
        </button> -->

        <a
          class="group flex flex-col items-center gap-3"
          href="https://microsoftedge.microsoft.com/addons/detail/clickshot/dhcgjgnkieiichjokpmabpbchgnlpngn"
          target="_blank"
          rel="noopener noreferrer"
        >
          <UIcon
            name="i-logos-microsoft-edge"
            class="w-12 h-12 transition-transform group-hover:scale-110"
          />
          <span class="text-xs text-gray-500 dark:text-gray-400">
            Edge Store
          </span>
        </a>
      </div>
    
    </UContainer>
  </section>
</template>

<template>
  <section class="relative overflow-hidden">
    <!-- Gradient -->
    <div class="bg-linear-to-br from-primary/20 via-indigo-500/10 to-purple-500/20" >

    <UContainer class="relative py-24">
      <div class="grid md:grid-cols-2 gap-12 items-center">
        <!-- Text -->
        <div>
          <h1 class="text-4xl md:text-5xl font-bold leading-tight">
           Stay focused. Revisit the exact moment later.
          </h1>

          <p class="mt-6 text-lg text-gray-500 dark:text-gray-400">
            Instantly take video notes with screenshots and timestamps, so you can return to the exact moment later. Easy note taking without exiting the full screen.          
          </p>
          <div class="mt-8 flex gap-3">
            <UButton size="lg" href="#installNow" icon="i-heroicons-arrow-down-tray">Install Extension</UButton>
          </div>
        </div>

        <div class="relative">
         <video
        src="/video/one.mp4"
        autoplay
        loop
        muted
        playsinline
        class="w-full h-full object-cover rounded-xl"
      ></video>
        </div>
      </div>
    </UContainer>
  </div>

  </section>
</template>

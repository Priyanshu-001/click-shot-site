<template>
  <section class="relative overflow-hidden">
    <!-- Gradient -->
    <div class="bg-linear-to-br from-primary/20 via-indigo-500/10 to-purple-500/20" >

    <UContainer class="relative py-24">
      <div class="grid md:grid-cols-2 gap-12 items-center">
        <!-- Text -->
        <div>
          <h1 class="text-4xl md:text-5xl font-bold leading-tight">
           Turn YouTube moments into notes you can find again.
          </h1>

          <p class="mt-6 text-lg text-gray-500 dark:text-gray-400">
            ClickShot is a Chrome extension for people who learn from video. Capture a screenshot, add a note, and keep a timestamped link to the exact moment — without leaving full-screen mode.
          </p>
          <p class="mt-4 text-sm text-gray-500 dark:text-gray-400">
            Perfect for students, researchers, and anyone taking notes from YouTube or HTML5 video.
          </p>
          <div class="mt-8 flex gap-3">
            <UButton size="lg" href="#installNow" icon="i-heroicons-arrow-down-tray">Install Extension</UButton>
            <UButton size="lg" href="#demo" icon="i-heroicons-eye" variant="outline">Watch Demo</UButton>

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

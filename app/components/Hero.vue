<template>
  <section class="relative overflow-hidden">
    <!-- Gradient -->
    <div class="absolute inset-0 bg-linear-to-br from-primary/20 via-indigo-500/10 to-purple-500/20" />

    <UContainer class="relative py-24">
      <div class="grid md:grid-cols-2 gap-12 items-center">
        <!-- Text -->
        <div>
          <h1 class="text-4xl md:text-5xl font-bold leading-tight">
            Capture key movements without interrupting your study.
          </h1>

          <p class="mt-6 text-lg text-gray-500 dark:text-gray-400">
            Instantly screenshot videos with timestamps and notes — stay focused while learning.
          </p>

          <div class="mt-8 flex gap-3">
            <UButton size="lg" href="#installNow" icon="i-heroicons-arrow-down-tray">Install Extension</UButton>
          </div>
        </div>

        <!-- GIF placeholder -->
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
  </section>
</template>

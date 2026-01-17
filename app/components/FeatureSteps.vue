<template>
  <UContainer class="py-24">
    <!-- Title -->
    <div class="text-center mb-20">
      <h2 class="text-3xl md:text-4xl font-bold">
        How ClickShot helps you in 3 steps
      </h2>
      <p class="mt-4 text-gray-500 dark:text-gray-400">
        Capture, remember, and reuse what actually matters.
      </p>
    </div>

    <!-- Step 1 -->
    <div class="grid md:grid-cols-2 gap-12 items-center mb-24">
      <div>
        <span class="text-primary font-semibold">Step 1</span>
        <h3 class="text-2xl font-semibold mt-2">
          Capture without pausing your brain
        </h3>
        <p class="mt-4 text-gray-500 dark:text-gray-400">
          Press <strong>Ctrl + Shift + L</strong> (customizable) to instantly
          capture and annotate key movements while you’re learning — no pause,
          no context switch.
        </p>
      </div>

         <video
  src="/video/one.mp4"
  autoplay
  loop
  muted
  controls
  playsinline
  class="w-full h-full object-cover rounded-xl"
></video>
    </div>

    <!-- Step 2 -->
    <div class="grid md:grid-cols-2 gap-12 items-center mb-24">
      <div class="md:order-2">
        <span class="text-primary font-semibold">Step 2</span>
        <h3 class="text-2xl font-semibold mt-2">
          Everything saved exactly where it happened
        </h3>
        <p class="mt-4 text-gray-500 dark:text-gray-400">
          All your notes live in ClickShot’s home — each one linked directly
          to the exact video moment you captured.
        </p>
      </div>

        <video
  src="/video/two.mp4"
  autoplay
  loop
  muted
  controls
  playsinline
  class="w-full h-full object-cover rounded-xl"
></video>
    </div>

    <!-- Step 3 -->
    <div class="grid md:grid-cols-2 gap-12 items-center">
      <div>
        <span class="text-primary font-semibold">Step 3</span>
        <h3 class="text-2xl font-semibold mt-2">
          Export notes wherever you think best
        </h3>
        <p class="mt-4 text-gray-500 dark:text-gray-400">
          Copy notes in one click to your favorite note-taking app for syncing,
          revision, and long-term storage.
        </p>
      </div>
   <video
  src="/video/three.mp4"
  autoplay
  loop
  muted
  controls
  playsinline
  class="w-full h-full object-cover rounded-xl" />
    </div>
  </UContainer>
</template>

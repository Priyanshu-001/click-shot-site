<template>
  <UContainer class="py-24">
    <!-- Title -->
      <div class="text-center mb-20">
        <h2 class="text-3xl md:text-4xl font-bold">
          How ClickShot works
        </h2>
        <p class="mt-4 text-gray-500 dark:text-gray-400">
        Save the moment, keep the timestamp, and reuse your notes anywhere.
        </p>
      </div>

    <!-- Step 1 -->
    <div class="grid md:grid-cols-2 gap-12 items-center mb-24">
      <div>
        <span class="text-primary font-semibold">Step 1</span>
        <h3 class="text-2xl font-semibold mt-2">
          Capture without leaving full screen
        </h3>
        <p class="mt-4 text-gray-500 dark:text-gray-400">
          Press <strong>Ctrl + Shift + K</strong> (customizable) to save a screenshot and note from YouTube or HTML5 video without breaking your flow.
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
          Every note keeps the exact timestamp
        </h3>
        <p class="mt-4 text-gray-500 dark:text-gray-400">
          Each note links back to the exact video moment you captured, so you can revisit it later in one click.
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
          Copy notes to your note app
        </h3>
        <p class="mt-4 text-gray-500 dark:text-gray-400">
          Export your timestamped notes to Obsidian, OneNote, or any note-taking app you use.
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

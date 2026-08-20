<template>
  <section class="relative">
    <!-- Background -->
    <div
      class="bg-linear-to-br
             from-slate-50 via-indigo-50/40 to-purple-50
             dark:from-gray-950 dark:via-indigo-950/30 dark:to-purple-950/30"
    >

    <UContainer class="relative py-24">
      <!-- Heading -->
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold">
          Why you’ll love ClickShot
        </h2>
        <p class="mt-4 text-gray-500 dark:text-gray-400">
          Easy to use, fast and simple.
        </p>
      </div>

      <!-- Grid -->
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <FeatureCard
          icon="i-heroicons-pencil-square"
          title="Annotate instantly"
          desc="Capture screenshots and write notes the moment something important happens on YouTube or HTML5 video."
        />
        <FeatureCard
          icon="i-heroicons-arrow-path"
          title="Jump back precisely"
          desc="Every note links directly to the exact video moment."
        />
        <FeatureCard
          icon="i-heroicons-command-line"
          title="Keyboard-first"
          desc="Stay in flow using shortcuts instead of menus."
        />
        <FeatureCard
          icon="i-heroicons-arrow-up-on-square"
          title="Export anywhere"
          desc="Copy timestamped notes to Obsidian, OneNote, or any app you prefer."
        />
        <FeatureCard
          icon="i-heroicons-lock-closed"
          title="100% local & private"
          desc="Everything stays on your machine. No uploads. No tracking."
        />
        <FeatureCard
          icon="i-heroicons-pencil"
          title="Edit anytime"
          desc="Update and refine notes whenever understanding improves."
        />
      </div>
    </UContainer>
    </div>
  </section>
</template>

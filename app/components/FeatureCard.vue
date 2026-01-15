<template>
  <UCard
    class="group transition-all duration-300
           hover:-translate-y-1 hover:shadow-lg"
  >
    <UIcon
      :name="icon"
      class="w-7 h-7 text-primary transition-transform duration-300
             group-hover:scale-125"
    />

    <h3 class="mt-4 font-semibold">
      {{ title }}
    </h3>

    <p class="mt-2 text-sm text-gray-500 dark:text-gray-400">
      {{ desc }}
    </p>
  </UCard>
</template>

<script setup lang="ts">
defineProps<{
  icon: string
  title: string
  desc: string
}>()
</script>

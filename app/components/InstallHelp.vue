<template>
  <UModal title="Thanks for installing ClickShot">
     <template #body>
      <UCard >

      <div class="space-y-4 text-sm">
        <p class="text-gray-600 dark:text-gray-400">
          Here’s how to get started quickly:
        </p>

        <ul class="space-y-3">
          <li class="flex gap-2">
            <span>🎯</span>
            <span>
              Press <b>Ctrl + Shift + K</b> to start capturing and annotating
              key moments (shortcut is customizable).
              If the shortcut does not work then please change the hotkey.
            </span>
            
          </li>
          
          <li class="flex gap-2">
            <span> 👆 </span>
            <span> Click on the extension button on tool bar to get option to view home and edit video note shortcut. </span>
          </li>
          <li class="flex gap-2">
            <span>📂</span>
            <span>
              View all your notes in the extension home, each linked to the
              exact video timestamp.
            </span>
          </li>

          <li class="flex gap-2 text-yellow-700 dark:text-yellow-400">
            <span>⚠️</span>
            <span>
              Notes are stored <b>locally</b>. Make sure to back them up —
              there’s no sync yet.
            </span>
          </li>

          <li class="flex gap-2 text-red-700 dark:text-red-400">
            <span>🗑️</span>
            <span>
              Uninstalling the extension will permanently remove all notes.
            </span>
          </li>
        </ul>
      </div>

      <template #footer>
        <div class="flex justify-end">
          <UButton @click="close">Got it</UButton>
        </div>
      </template>
    </UCard>
    </template>
    
  </UModal>
</template>

<script setup lang="ts">

const emit = defineEmits(["close"])

function close() {
  emit("close")
}

const openShortcutPage = () => {
  window.open('chrome://extensions/shortcuts', '_blank');
};
</script>

<style scoped>
    .yellow-alert {
  background: #fff7cc;
  color: #7a5d00;
  padding: 6px 10px;
  border-radius: 6px;
  font-size: 0.85rem;
  border: 1px solid #ffe08a;
}

.yellow-alert a {
  font-weight: 600;
  cursor: pointer;
  text-decoration: underline;
}

</style>

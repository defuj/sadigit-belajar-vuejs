<script setup>
defineProps({
  text: String,
  type: String
})
</script>

<template>
  <button v-if="type == 'primary'" class="text-black bg-white rounded-md px-6 py-3 my-2">
    {{ text }}
  </button>

  <button v-else class="text-white bg-neutral-700 rounded-md px-6 py-3 my-2">{{ text }}</button>
</template>

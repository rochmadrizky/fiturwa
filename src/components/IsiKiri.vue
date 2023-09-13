<template>
  <div
    class="p-4 flex"
    :class="[props.type === 'kiri' ? 'justify-start' : 'justify-end']"
  >
    <div
      class="relative w-[165px] p-2 rounded-lg bg-white gap-4 flex items-center"
    >
      <span class="text-sm"><slot></slot></span>
      <span class="text-[10px] absolute bottom-0 right-2">13:38</span>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  type: String,
});
</script>

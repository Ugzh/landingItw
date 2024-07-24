<script setup>
defineProps({
  msg: String,
  tag: String,
});
</script>

<template>
  <a
    href="#"
    class="flex bg-white p-2 rounded-full gap-4 max-w-[75%] w-full drop-shadow"
  >
    <span
      class="text-white flex gap-2 bg-gradient-to-t from-[#197ce7] to-[#23bbfe] px-3 rounded-2xl drop-shadow-sm font-bold"
      >{{ tag }}</span
    >
    {{ msg }}</a
  >
</template>

<style scoped></style>

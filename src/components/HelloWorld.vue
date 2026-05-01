<script setup>
defineProps({
  pesan: String,
  deskripsi: String
})
</script>

<template>
  <h2>hello {{ pesan }}</h2>
  <p>{{ deskripsi }}</p>
</template>
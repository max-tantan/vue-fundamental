<script setup>
defineProps({
    pesan: {
        type: String,
        default: 'Hello World'
    },
    deskripsi: {
        type: String,
        default: 'Deskripsi default'
    }
})
</script>

<template>
    <h2>{{ pesan }}</h2>
    <p>{{ deskripsi }}</p>
</template>

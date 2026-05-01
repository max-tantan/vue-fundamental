<script setup>
import { ref } from 'vue';

const nama =ref('');
</script>

<template>
    <input @input="e => nama.value = e.target.value" placeholder="Masukkan nama" type="text">
    <p>Hello !{{ nama }}</p>
</template>
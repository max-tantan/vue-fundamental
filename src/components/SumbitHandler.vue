'<script setup>
import { ref } from 'vue'

const email = ref('')

const handlesumbit = () => {
    alert(' Email anda dikonfirmasi' + email.value)
}
</script>

<template>
<form @submit.prevent="handlesumbit">
    <input v-model="email" placeholder="Masukkan email" type="email">
    <button type="submit">Kirim</button>
</form>
</template>
<script setup>
import HelloWorld from './components/HelloWorld.vue'
import PropsDefault from './components/PropsDefault.vue'
</script>

<template>
  <HelloWorld pesan="Vue.js" deskripsi="Framework JavaScript untuk membangun antarmuka pengguna" />
  <HelloWorld pesan="JavaScript" deskripsi="Bahasa pemrograman yang digunakan untuk mengembangkan aplikasi web" />
  <HelloWorld pesan="Web Development" deskripsi="Proses pembuatan situs web dan aplikasi berbasis web" />
  <PropsDefault />
</template>

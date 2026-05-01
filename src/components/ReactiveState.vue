<script setup>
import { reactive } from 'vue';

const user = reactive({
    name: "Fatan Nur Rizqi",
    age: 17,
})

const updateAge = () => {
    user.age++
}

const backeage = () => {
    user.age--
}
const resetAge = () => {
    user.age = 17
}
</script>

<template>
    <div class="container">
        <h1>Name: {{ user.name }}</h1>
        <h2>Age: {{ user.age }}</h2>
        <button @click="updateAge">Increment Age</button>
        <button @click="backeage">Decrement Age</button>
        <button @click="resetAge">Reset Age</button>
    </div>
</template>

<style setup>
.container {
    display: flex;
    flex-direction: column;
    align-items: start;
    gap: 10px;
}
</style>

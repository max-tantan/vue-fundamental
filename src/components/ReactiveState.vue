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
</script>

<template>
    <div>
        <h1>Name: {{ user.name }}</h1>
        <h2>Age: {{ user.age }}</h2>
        <button @click="updateAge">Increment Age</button>
        <button @click="backeage">Decrement Age</button>
    </div>
</template>

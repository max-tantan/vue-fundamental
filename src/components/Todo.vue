<script setup>
import { reactive } from 'vue'

const todos = reactive([])

const addTodo = () => {
    todos.push('Belajar Vue.js')
}

const removeTodo = (index) => {
    todos.splice(index, 1)
}
</script>

<template>
    <div>
        <button @click="addTodo">Tambah Todo</button>
        <button @click="removeTodo">Hapus Todo</button>
        <ul>
            <li v-for="(todo, index) in todos" :key="index">
                {{ todo }}
            </li>
        </ul>
    </div>
</template>

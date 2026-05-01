<script setup>
import HelloWorld from './components/HelloWorld.vue'
import PropsDefault from './components/PropsDefault.vue'
import RefState from './components/RefState.vue'
import ReactiveState from './components/ReactiveState.vue'
import Todo from './components/Todo.vue'
import InputHandler from './components/InputHandler.vue'
import SumbitHandler from './components/SumbitHandler.vue'
</script>

<template>
 <div class="main">

   <PropsDefault />
   <ReactiveState />
   <Todo />
    <InputHandler />
    <SumbitHandler />
 </div>
</template>

<style setup>
.main {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
}
</style>

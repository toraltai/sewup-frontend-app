<script setup>
const { data, error, status } = useFetch('http://localhost:8000/list',{
    method: 'GET',
});
const todos = computed(() => data.value.todos)
</script>

<template>
    <div class="flex justify-center">
    <div class="grid grid-cols-1 sm:grid-cols-2 gap-10">
        <article class="card" v-for="todo in todos" :key="todo.id">
            <h1>{{ todo.name }}</h1>
        </article>
    </div>
    </div>
</template>

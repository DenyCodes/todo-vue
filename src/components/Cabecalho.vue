<script setup>
const props = defineProps(['tarefasPendentes'])
</script>
<template>
    <header class="p-5 mb-4 mt-4 bg-light rounded-3">
        <h1>Minhas Tarefas</h1>
        <p>
            você possui {{ props.tarefasPendentes }} tarefas Pendentes
        </p>
    </header>
</template>
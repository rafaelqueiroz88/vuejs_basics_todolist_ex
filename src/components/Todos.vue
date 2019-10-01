<template>
    <div>
        <h1>Todos</h1>
        <h3>TODO list here</h3>
        <div v-for="todo in todos">
            <h3>{{ todo.title }}</h3>
        </div>
    </div>
</template>

<!-- props pegará o valor passado através do "v-bind:todos" e assim podemos capturar os valores com v-for variável ... in todos -->
<script>
    export default {
        name: "Todos",
        props: ["todos"]
    }
</script>

<style scoped>
    div {
        padding-left: 30px;
    }
</style>
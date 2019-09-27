<template>
  <div id="app">
    <Menu />
    <Todos v-bind:todos="todos"/>
  </div>
</template>

<script>
  // Voltar em: https://youtu.be/Wy9q22isx3U?t=1141

  import Todos from './components/Todos';
  import Menu from './components/Menu';

  export default {
    name: 'app',
    components: {
      Todos,
      Menu
    },
    data() {
      return {
        todos: [
          {
            id: 1,
            title: "Todo 1",
            completed: false
          },
          {
            id: 2,
            title: "Todo 2",
            completed: false
          },
          {
            id: 3,
            title: "Todo 3",
            completed: false
          }
        ]
      }
    }
  }
</script>

<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
</style>
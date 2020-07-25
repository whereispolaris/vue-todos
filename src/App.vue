<template>
  <div id="app">
    <Todos v-bind:todos="todos" v-bind:key="type" />
  </div>
</template>

<script>
import Todos from "./components/Todos";
export default {
  name: "App",
  components: {
    Todos
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title: "Todo one",
          completed: false
        },
        {
          id: 2,
          title: "Todo two",
          completed: false
        },
        {
          id: 3,
          title: "Todo three",
          completed: false
        }
      ]
    };
  }
};
</script>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
</style>

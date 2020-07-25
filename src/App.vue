<template>
  <div id="app">
    <Todos title="Todos" />
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

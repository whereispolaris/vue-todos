<template>
  <div id="app"></div>
</template>

<script>
export default {
  name: "App",
  components: {},
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

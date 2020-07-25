<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>
<script>
export default {
  name: "Todos",
  props: {
    title: String
  }
};
</script>
<style scoped>
</style>
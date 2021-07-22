<template>
  <div id="app">
    <AutoComplete :items="items" />
  </div>
</template>

<script>
import AutoComplete from "./components/AutoComplete";

export default {
  name: "App",
  components: {
    AutoComplete
  },
  data() {
    return {
      items: [
        { title: "Alex", id: 1 },
        { title: "Ben", id: 2 },
        { title: "Carl", id: 3 },
        { title: "David", id: 4 },
        { title: "Alex", id: 1 },
        { title: "Ben", id: 2 },
        { title: "Carl", id: 3 },
        { title: "David", id: 4 }
      ]
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

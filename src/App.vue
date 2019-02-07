<template>
  <div id="app">
    <top></top>
  </div>
</template>

<script>
import top from "./components/header.vue";

export default {
  name: "app",
  components: {
    top
  }
};
</script>

<style>
#app {
  /* font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>

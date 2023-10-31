<template>
  <div id="app">
    <PagesContainer />
  </div>
</template>

<script>
import PagesContainer from "./components/PagesContainer.vue";

export default {
  name: "App",
  components: {
    PagesContainer,
  },
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

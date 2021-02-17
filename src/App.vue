<template>
  <Home class="Home" />
</template>

<script>
import Home from "./Pages/Home";
export default {
  name: "App",
  components: {
    Home,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
li {
  list-style: none;
}
#app {
  font-family: "Jost", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: black;
  font-size: 20px;
}
</style>

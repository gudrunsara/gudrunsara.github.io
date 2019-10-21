<template>
  <div id="app">
    <Header />
    <NavBar />
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Header from "./components/Header.vue";

export default {
  name: "app",
  components: {
    NavBar,
    Header
  }
};
</script>

<style>
/* Global styling. */
#app {
  font-family: Montserrat, "Open Sans", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>

<template>
  <div id="app">
    <section id="Header" class="">
      <NavBar />
    </section>
    <section id="About" class="big-and-red"></section>
    <section id="Timeline" class="big-and-blue"></section>
    <section id="Portfolio" class="big-and-green"></section>
    <section id="Contact" class="big-and-yellow"></section>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";

export default {
  name: "app",
  components: {
    NavBar
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
.big-and-red {
  height: 300px;
  width: 100%;
  background-color: red;
}
.big-and-blue {
  height: 300px;
  width: 100%;
  background-color: blue;
}
.big-and-green {
  height: 300px;
  width: 100%;
  background-color: green;
}
.big-and-yellow {
  height: 300px;
  width: 100%;
  background-color: yellow;
}
</style>

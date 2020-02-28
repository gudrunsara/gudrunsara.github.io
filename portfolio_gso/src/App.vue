<template>
  <div id="app">
    <Header />
    <!-- Navigation bar: -->
    <NavBar />
    <!-- Site sections: -->
    <div class="site-body">
      <section id="About" class="big-and-red"></section>
      <section id="Timeline" class="big-and-blue"></section>
      <section id="Portfolio" class="big-and-green"></section>
      <section id="Contact" class="big-and-yellow"></section>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import NavBar from "./components/NavBar.vue";

export default {
  name: "app",
  components: {
    Header,
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
}
.border {
  border: 1pt solid lightgray;
}
/* TEMP: do I need this? */
/* .site-body {
  padding-top: 58px;
} */
/* TEMP: temporary color and size schemes for development. */
.big-and-red {
  height: 600px;
  width: 100%;
  background-color: red;
}
.big-and-blue {
  height: 600px;
  width: 100%;
  background-color: blue;
}
.big-and-green {
  height: 600px;
  width: 100%;
  background-color: green;
}
.big-and-yellow {
  height: 600px;
  width: 100%;
  background-color: yellow;
}
</style>

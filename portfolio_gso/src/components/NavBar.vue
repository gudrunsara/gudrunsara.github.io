<template>
  <div class="border">
    <nav class="page-navigation">
      <ul class="nav-bar">
        <li><a href="#about">About</a></li>
        <li><a href="#section-about">About</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#about">About</a></li>
      </ul>
    </nav>
    <p>hello</p>
    <p>hello</p>
    <p>hello</p>
    <p>hello</p>
    <p>hello</p>
    <p>hello</p>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.border {
  border: 1pt solid lightgray;
}
nav.page-navigation {
  background-color: green;
  position: fixed;
  top: 10%;
  width: 100%;
}
</style>

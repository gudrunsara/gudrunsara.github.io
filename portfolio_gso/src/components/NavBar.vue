<template>
  <div class="border">
    <b-navbar>
      <b-navbar-brand href="#About"> Gudrun </b-navbar-brand>
      <b-navbar-nav>
        <b-nav-item href="#About">About</b-nav-item>
        <b-nav-item href="#Timeline">Timeline</b-nav-item>
        <b-nav-item href="#Portfolio">Portfolio</b-nav-item>
        <b-nav-item href="#Contact">Contact</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
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
</style>

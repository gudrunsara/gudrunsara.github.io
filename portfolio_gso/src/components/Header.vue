<template>
  <div class="border header">
    <p>Hello from header!</p>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.border {
  border: 1pt solid rgb(238, 177, 87);
}
.header {
  height: 100vh;
  background-color: rgb(238, 177, 87);
}
</style>

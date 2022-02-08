<template>
  <Navbar />
  <div class="row">
    <Card />
    <Card />
    <Card />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Card from "./components/Card.vue";
export default {
  name: "App",
  components: {
    Navbar,
    Card,
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
  margin: 0;
}
.row {
  display: flex;
  justify-content: space-evenly;
}
</style>

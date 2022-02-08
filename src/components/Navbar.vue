<template>
  <nav class="nav-bar">
    <span>Vue</span>
    <span>Favorites</span>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  props: {
    menu: Array,
  },
};
</script>

<style scoped>
.nav-bar {
  color: white;
  font-weight: 600;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #42b983;
  height: 2.5rem;
  padding-left: 10px;
  padding-right: 10px;
}
</style>

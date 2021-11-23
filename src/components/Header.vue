<template>
  <header>
    <div class="container">
      <img src="../assets/dark-logo.png" alt="logo" />
      <Nav></Nav>
    </div>
  </header>
</template>

<script>
import Nav from "./header-components/Nav.vue";
export default {
  name: "Header",
  components: { Nav },
};
</script>

<style lang="scss">
@import "../styles/header.scss";
</style>
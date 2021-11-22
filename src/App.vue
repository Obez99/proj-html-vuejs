<template>
  <div id="app">
    <Header></Header>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
export default {
  name: "App",
  components: { Header },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";

a {
  color: black;
  text-decoration: none;
}
</style>

<template>
  <div id="app">
    <Header></Header>
    <Download></Download>
    <Courses></Courses>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Download from "./components/Download.vue";
import Courses from "./components/Courses.vue";
export default {
  name: "App",
  components: { Header, Download, Courses },
};
</script>

<style lang="scss">
@import "./styles/app.scss";
</style>

<template>
  <div id="app">
    <Header></Header>
    <Download></Download>
    <Courses></Courses>
    <SmartTutoring></SmartTutoring>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Download from "./components/Download.vue";
import Courses from "./components/Courses.vue";
import SmartTutoring from "./components/SmartTutoring.vue";
export default {
  name: "App",
  components: { Header, Download, Courses, SmartTutoring },
};
</script>

<style lang="scss">
@import "./styles/app.scss";
</style>

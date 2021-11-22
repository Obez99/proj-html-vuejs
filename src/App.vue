<template>
  <div id="app">
    <Header></Header>
    <DownloadSection></DownloadSection>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import DownloadSection from "./components/DownloadSection.vue";
export default {
  name: "App",
  components: { Header, DownloadSection },
};
</script>

<style lang="scss">
@import "./styles/app.scss";
</style>

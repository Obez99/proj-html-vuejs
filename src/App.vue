<template>
  <div id="app">
    <Header></Header>
    <Main :mainPath="mainPath"></Main>
    <Footer :mainPath="mainPath"></Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },

  data() {
    return {
      mainPath: "https://maxcoach.thememove.com/main/",
    };
  },
};
</script>

<style lang="scss">
@import "./styles/app.scss";
</style>

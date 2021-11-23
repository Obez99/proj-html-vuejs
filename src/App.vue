<template>
  <div id="app">
    <Header></Header>
    <Download></Download>
    <Courses></Courses>
    <SmartTutoring></SmartTutoring>
    <VideoSection></VideoSection>
    <TopLearners></TopLearners>
    <Statistics></Statistics>
    <BestBlogs></BestBlogs>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Download from "./components/Download.vue";
import Courses from "./components/Courses.vue";
import SmartTutoring from "./components/SmartTutoring.vue";
import VideoSection from "./components/VideoSection.vue";
import TopLearners from "./components/TopLearners.vue";
import Statistics from "./components/Statistics.vue";
import BestBlogs from "./components/BestBlogs.vue";
export default {
  name: "App",
  components: {
    Header,
    Download,
    Courses,
    SmartTutoring,
    VideoSection,
    TopLearners,
    Statistics,
    BestBlogs,
  },
};
</script>

<style lang="scss">
@import "./styles/app.scss";
</style>

<template>
  <main>
    <Download></Download>
    <Courses></Courses>
    <SmartTutoring></SmartTutoring>
    <VideoSection></VideoSection>
    <TopLearners></TopLearners>
    <Statistics></Statistics>
    <BestBlogs></BestBlogs>
    <Newsletters></Newsletters>
    <SideBar></SideBar>
  </main>
</template>

<script>
import Download from "./main-components/Download.vue";
import Courses from "./main-components/Courses.vue";
import SmartTutoring from "./main-components/SmartTutoring.vue";
import VideoSection from "./main-components/VideoSection.vue";
import TopLearners from "./main-components/TopLearners.vue";
import Statistics from "./main-components/Statistics.vue";
import BestBlogs from "./main-components/BestBlogs.vue";
import Newsletters from "./main-components/Newsletters.vue";
import SideBar from "./main-components/SideBar.vue";
export default {
  name: "Main",
  components: {
    Download,
    Courses,
    SmartTutoring,
    VideoSection,
    TopLearners,
    Statistics,
    BestBlogs,
    Newsletters,
    SideBar,
  },
};
</script>

<style lang="scss">
</style>
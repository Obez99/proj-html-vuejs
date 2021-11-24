<template>
  <section>
    <!--Smart Tutoring Header !-->
    <div class="smart-tutoring-header text-center">
      <p>MAXCOACH AVAILABLE COURSES</p>
      <h2>Access <a href="#">Smart Tutoring</a> Program For Benefits</h2>
    </div>

    <div class="container">
      <div class="row justify-content-between">
        <Benefit
          v-for="(benefit, i) in benefitsList"
          :key="i"
          :benefit="benefitsList[i]"
        ></Benefit>
      </div>
    </div>
  </section>
</template>

<script>
import Benefit from "./main-sub-components/Benefit.vue";
export default {
  name: "SmartTutoring",
  components: { Benefit },
  props: { mainPath: String },

  data() {
    return {
      benefitsList: [
        {
          image: require("../../assets/home-2-image-box-01.png"),
          title: "Customize Preferences",
          description:
            "Learners are given the right to arrange and customize their study schedule and timetable based on preferences.",
          linkText: "Start here",
          linkRef: this.mainPath + "about-us-03",
        },
        {
          image: require("../../assets/home-2-image-box-01.png"),
          title: "Cloud Storage",
          description:
            "You can store online lessons via online cloud or download to your device and revise lessons on the way.",
          linkText: "Get Free Quote",
          linkRef: this.mainPath + "about-us-03",
        },
        {
          image: require("../../assets/home-2-image-box-01.png"),
          title: "Multimedia Channels",
          description:
            "We provide study materials with various formats: video, audio, slides, doc, prints, books and applications.",
          linkText: "Start now",
          linkRef: this.mainPath + "about-us-03",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "../../styles/smarttutoring.scss";
</style>
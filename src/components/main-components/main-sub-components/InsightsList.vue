<template>
  <div class="col-4 most-viewed-list">
    <div>
      <p>ENJOYABLE INSIGHTS</p>
      <h2>Most Viewed <a href="#">Best Blogs</a></h2>
    </div>

    <ul>
      <Insight
        v-for="(insight, i) in insightsList"
        :key="i"
        :insight="insightsList[i]"
      ></Insight>
    </ul>
  </div>
</template>

<script>
import Insight from "./Insight.vue";
export default {
  name: "InsightsList",
  components: { Insight },
  props: { mainPath: String },
  data() {
    return {
      insightsList: [
        {
          title: "Become a Better Blogger: Content Planning",
          link: this.mainPath + "become-a-better-blogger-content-planning",
        },
        {
          title: "Promoting Your Online Business on Pinterest",
          link: this.mainPath + "promoting-your-online-business-on-pinterest",
        },
        {
          title: "Gamification and Game-Based Learning",
          link: this.mainPath + "gamification-and-game-based-learning",
        },
        {
          title: "Designing an Online Course from Expert's Perspective",
          link:
            this.mainPath +
            "designing-an-online-course-from-experts-perspective",
        },
        {
          title: "Why Online Courses Are the Future of Education",
          link:
            this.mainPath + "why-online-courses-are-the-future-of-education",
        },
      ],
    };
  },
};
</script>

<style>
</style>
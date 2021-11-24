<template>
  <section style="background-color: #f5f1ed">
    <div class="container">
      <div class="row justify-content-between">
        <InsightsList
          :mainPath="mainPath"
          :insightsList="insightsList"
        ></InsightsList>

        <Card
          v-for="(card, i) in cardsList"
          :key="i"
          :card="cardsList[i]"
        ></Card>
      </div>
    </div>
  </section>
</template>

<script>
import InsightsList from "./main-sub-components/InsightsList.vue";
import Card from "./main-sub-components/Card.vue";
export default {
  name: "BestBlogs",
  components: { InsightsList, Card },
  props: { mainPath: String },
  data() {
    return {
      cardsList: [
        {
          image: require("../../assets/artist-blog-03-480x352.jpeg"),
          title: "Brush Strokes Energize Trees in Paintings",
          date: "May 15, 2020",
          views: "688 views",
        },
        {
          image: require("../../assets/artist-blog-01-480x352.jpg"),
          title: "Pocket-Sized Notebooks Hold Miniature Paintings",
          date: "May 15, 2020",
          views: "603 views",
        },
      ],
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

<style lang="scss">
@import "../../styles/bestblogs.scss";
</style> 
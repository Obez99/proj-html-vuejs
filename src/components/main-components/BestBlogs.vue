<template>
  <section style="background-color: #f5f1ed">
    <div class="container">
      <div class="row justify-content-between">
        <InsightsList :mainPath="mainPath"></InsightsList>

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
    };
  },
};
</script>

<style lang="scss">
@import "../../styles/bestblogs.scss";
</style> 
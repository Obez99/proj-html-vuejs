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
  props: { mainPath: String, insightsList: Array },
};
</script>

<style>
</style>
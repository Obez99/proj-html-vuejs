<template>
  <div>
    <div class="reviews-container">
      <Review
        v-for="(review, i) in reviewsList"
        :key="i"
        :review="reviewsList[i]"
        :currentActive="currentActive"
      ></Review>
    </div>

    <!--Cards navigation dots!-->
    <div class="reviews-nav-dots">
      <i
        v-for="(dot, i) in reviewsList"
        :key="i"
        class="fa fa-circle"
        :class="dot.active ? 'active' : ''"
        @click="changeActive(i)"
      ></i>
    </div>
  </div>
</template>

<script>
import Review from "./Review.vue";
export default {
  name: "InsightsSlider",
  components: { Review },
  props: { reviewsList: Array, currentActive: Number },

  methods: {
    changeActive(i) {
      this.$emit("changeActive", i);
    },
  },
};
</script>

<style>
</style>
<template>
  <div class="col-3">
    <h5>Explore</h5>
    <ul class="explore-list">
      <li v-for="(item, i) in exploreList" :key="i">
        <a :href="item.link">{{ item.title }}</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Explore",
  props: { exploreList: Array },
};
</script>

<style>
</style>
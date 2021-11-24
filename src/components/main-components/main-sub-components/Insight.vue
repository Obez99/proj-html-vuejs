<template>
  <li>
    <i class="fa fa-long-arrow-right"></i
    ><a :href="insight.link">{{ insight.title }}</a>
  </li>
</template>

<script>
export default {
  name: "Insight",
  props: { insight: Object },
};
</script>

<style>
</style>
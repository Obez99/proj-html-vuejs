<template>
  <ul class="social-links">
    <li v-for="(social, i) in socialMediaList" :key="i">
      <a :href="social.link"><i :class="social.icon"></i></a>
    </li>
  </ul>
</template>

<script>
export default {
  name: "SocialMediaLinks",
  props: { socialMediaList: Array },
};
</script>

<style>
</style>
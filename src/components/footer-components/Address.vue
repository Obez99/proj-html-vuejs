<template>
  <div class="col-6">
    <h5>Address</h5>
    <ul>
      <li v-for="(item, i) in addressList" :key="i">
        <p>
          {{ item.content }}
          <span v-if="item.type === 'Phone'"
            >(9am - 5pm EST, Monday - Friday)</span
          >
        </p>
      </li>
    </ul>

    <SocialMediaLinks :socialMediaList="socialMediaList"></SocialMediaLinks>
  </div>
</template>

<script>
import SocialMediaLinks from "./SocialMediaLinks.vue";
export default {
  name: "Address",
  components: { SocialMediaLinks },
  props: {
    addressList: Array,
    socialMediaList: Array,
  },
};
</script>

<style>
</style>
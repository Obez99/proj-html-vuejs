<template>
  <!--Information!-->
  <div class="col-3">
    <h5>Information</h5>
    <ul>
      <li v-for="(item, i) in informationList" :key="i">
        <a :href="mainPath + item.link">{{ item.title }}</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Information",
  props: { informationList: Array, mainPath: String },
};
</script>

<style>
</style>
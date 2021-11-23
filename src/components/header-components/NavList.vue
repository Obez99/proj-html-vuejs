<template>
  <ul>
    <li v-for="(item, i) in items" :key="i">
      <span v-if="item.title"
        >{{ item.title }}<i class="fa fa-chevron-down"></i
      ></span>
      <a v-else :href="item.link"><i :class="item.icon"></i></a>
    </li>
  </ul>
</template>

<script>
export default {
  name: "NavList",
  props: {
    items: Array,
  },
};
</script>

<style lang="scss">
</style>
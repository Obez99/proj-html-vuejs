<template>
  <a :href="item.link"><i :class="item.icon"></i></a>
</template>

<script>
export default {
  name: "SidebarItem",
  props: { item: Object },
};
</script>

<style>
</style>
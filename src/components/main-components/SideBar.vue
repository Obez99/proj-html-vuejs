<template>
  <div class="sidebar">
    <SidebarItem
      v-for="(item, i) in sidebarItems"
      :key="i"
      :item="sidebarItems[i]"
    ></SidebarItem>
  </div>
</template>

<script>
import SidebarItem from "./main-sub-components/SidebarItem.vue";
export default {
  name: "SideBar",
  components: { SidebarItem },
  data() {
    return {
      sidebarItems: [
        {
          icon: "fa fa-list",
          title: "",
          link: "",
        },
        {
          icon: "fa fa-life-ring",
          title: "",
          link: "",
        },
        {
          icon: "fa fa-book",
          title: "",
          link: "",
        },
        {
          icon: "fa fa-shopping-cart",
          title: "",
          link: "",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "../../styles/sidebar.scss";
</style>
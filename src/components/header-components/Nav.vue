<template>
  <nav>
    <NavList :items="navlistItems"></NavList>
    <SearchBar></SearchBar>
  </nav>
</template>

<script>
import NavList from "./NavList.vue";
import SearchBar from "./SearchBar.vue";
export default {
  name: "Nav",
  components: {
    NavList,
    SearchBar,
  },
  data() {
    return {
      navlistItems: [
        {
          title: "Home",
          image: "",
          link: "",
        },
        {
          title: "Pages",
          image: "",
          link: "",
        },
        {
          title: "Courses",
          image: "",
          link: "",
        },
        {
          title: "Features",
          image: "",
          link: "",
        },
        {
          title: "Blog",
          image: "",
          link: "",
        },
        {
          title: "Shop",
          image: "",
          link: "",
        },
        {
          title: null,
          icon: "fa fa-user-o",
          link: "userprofile.html",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
</style>
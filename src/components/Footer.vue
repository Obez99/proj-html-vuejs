<template>
  <footer>
    <FooterLists :mainPath="mainPath"></FooterLists>

    <div>
      <p class="copyright-statement text-center">
        © 2020 Maxcoach. All Rights Reserved
      </p>
    </div>
  </footer>
</template>

<script>
import FooterLists from "./footer-components/FooterLists.vue";
export default {
  name: "Footer",
  components: { FooterLists },
  props: { mainPath: String },
};
</script>

<style lang="scss">
@import "../styles/footer.scss";
</style>
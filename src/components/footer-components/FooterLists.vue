<template>
  <div class="container">
    <div class="row">
      <Address
        :addressList="addressList"
        :socialMediaList="socialMediaList"
      ></Address>
      <Explore :exploreList="exploreList" :mainPath="mainPath"></Explore>
      <Information
        :informationList="informationList"
        :mainPath="mainPath"
      ></Information>
    </div>
  </div>
</template>

<script>
import Address from "./Address.vue";
import Explore from "./Explore.vue";
import Information from "./Information.vue";
export default {
  name: "FooterLists",
  components: { Address, Explore, Information },
  props: { mainPath: String },
  data() {
    return {
      addressList: [
        {
          type: "Street",
          content: "382 NE 191st St # 87394 Miami, FL 33179-3899",
        },
        {
          type: "Phone",
          content: "+1 (305) 547-9909",
        },
        {
          type: "Email",
          content: "support@maxcoach.com",
        },
      ],
      exploreList: [
        {
          title: "Start Here",
          link: "start-here/",
        },
        {
          title: "Success Story",
          link: "success-story/",
        },
        {
          title: "Blog",
          link: "blog/",
        },
        {
          title: "Courses",
          link: "courses/",
        },
        {
          title: "About us",
          link: "about-us-01/",
        },
        {
          title: "Contact us",
          link: "contact-us/",
        },
      ],
      informationList: [
        {
          title: "Membership",
          link: "membership-account/membership-levels",
        },
        {
          title: "Purchase Guide",
          link: "purchase-guide",
        },
        {
          title: "Privacy Policy",
          link: "privacy-policy",
        },
        {
          title: "Terms of services",
          link: "terms-of-service",
        },
      ],
      socialMediaList: [
        {
          name: "facebook",
          link: "https://www.facebook.com",
          icon: "fa fa-facebook-square",
        },
        {
          name: "twitter",
          link: "https://www.twitter.com",
          icon: "fa fa-twitter",
        },
        {
          name: "instagram",
          link: "https://www.instagram.com",
          icon: "fa fa-instagram",
        },
        {
          name: "linkedin",
          link: "https://www.linkedin.com",
          icon: "fa fa-linkedin-square",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
</style>
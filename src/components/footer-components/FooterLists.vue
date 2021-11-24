<template>
  <div class="container">
    <div class="row">
      <Address
        :addressList="addressList"
        :socialMediaList="socialMediaList"
      ></Address>
      <Explore :exploreList="exploreList"></Explore>
      <Information :informationList="informationList"></Information>
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
          link: "https://maxcoach.thememove.com/main/start-here/",
        },
        {
          title: "Success Story",
          link: "https://maxcoach.thememove.com/main/success-story/",
        },
        {
          title: "Blog",
          link: "https://maxcoach.thememove.com/main/blog/",
        },
        {
          title: "Courses",
          link: "https://maxcoach.thememove.com/main/courses/",
        },
        {
          title: "About us",
          link: "https://maxcoach.thememove.com/main/about-us-01/",
        },
        {
          title: "Contact us",
          link: "https://maxcoach.thememove.com/main/contact-us/",
        },
      ],
      informationList: [
        {
          title: "Membership",
          link: "https://maxcoach.thememove.com/main/membership-account/membership-levels",
        },
        {
          title: "Purchase Guide",
          link: "https://maxcoach.thememove.com/main/purchase-guide",
        },
        {
          title: "Privacy Policy",
          link: "https://maxcoach.thememove.com/main/privacy-policy",
        },
        {
          title: "Terms of services",
          link: "https://maxcoach.thememove.com/main/terms-of-service",
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
<template>
  <section>
    <!--Download section content!-->
    <div class="container">
      <div class="row d-flex align-items-center justify-content-between">
        <!--Description and download!-->
        <div class="col-4">
          <h1>Distant learning for further expansion</h1>
          <p>
            Learning is a life-long journey that in fact we never find the
            terminate stop. Stop searching, enjoy the process.
          </p>
          <button class="btn btn-primary">
            <i class="fa fa-download"></i> Download free guide
          </button>
          <p>
            Have questions?
            <a href="#"
              >Get Free Sample <i class="fa fa-long-arrow-right"></i
            ></a>
          </p>
        </div>

        <!--Big image!-->
        <div class="col-7 text-end position-relative mb-5 jumbo-image">
          <img
            src="../../assets/about-me-profile-ohm4dxoearqbxny7q3bq1pzbdgofdx0tobbeqcvzd0.jpg"
            alt="jumbo-image"
            class="rounded-circle"
          />
          <img src="../../assets/maxcoach-shape-08.png" alt="" class="fx1" />
          <img src="../../assets/maxcoach-shape-08.png" alt="" class="fx2" />

          <img
            src="../../assets/maxcoach-shape-07-150x150.png"
            alt=""
            class="fx3"
          />

          <img src="../../assets/maxcoach-shape-02.png" alt="" class="fx4" />

          <div class="empty-circle fx10"></div>
        </div>
      </div>

      <!--Clients section!-->
      <Clients :clientsList="clientsList"></Clients>
    </div>
  </section>
</template>

<script>
import Clients from "./main-sub-components/Clients.vue";
export default {
  name: "Download",
  components: { Clients },
  data() {
    return {
      clientsList: [
        {
          image: require("../../assets/client-logo-01.png"),
          name: "stylus",
        },
        {
          image: require("../../assets/client-logo-02.png"),
          name: "company",
        },
        {
          image: require("../../assets/client-logo-03.png"),
          name: "brook",
        },
        {
          image: require("../../assets/client-logo-04.png"),
          name: "pencil",
        },
        {
          image: require("../../assets/client-logo-05.png"),
          name: "itsalive",
        },
        {
          image: require("../../assets/client-logo-06.png"),
          name: "sixbase",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "../../styles/download.scss";
</style>
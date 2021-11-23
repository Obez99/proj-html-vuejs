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
        <div class="col-7 text-end position-relative mb-5">
          <img
            src="../../assets/about-me-profile-ohm4dxoearqbxny7q3bq1pzbdgofdx0tobbeqcvzd0.jpg"
            alt="jumbo-image"
            class="rounded-circle"
          />
          <img
            src="../../assets/maxcoach-shape-08.png"
            alt=""
            class="position-absolute fx1"
          />
          <img
            src="../../assets/maxcoach-shape-08.png"
            alt=""
            class="position-absolute fx2"
          />

          <img
            src="../../assets/maxcoach-shape-07-150x150.png"
            alt=""
            class="position-absolute fx3"
          />

          <img
            src="../../assets/maxcoach-shape-02.png"
            alt=""
            class="position-absolute fx4"
          />
        </div>
      </div>

      <!--Clients section!-->
      <div class="clients-list mt-5">
        <ul class="row align-items-center">
          <li class="col-2 text-center">
            <img src="../../assets/client-logo-01.png" alt="stylus-logo" />
          </li>

          <li class="col-2 text-center">
            <img src="../../assets/client-logo-02.png" alt="company-logo" />
          </li>

          <li class="col-2 text-center">
            <img src="../../assets/client-logo-03.png" alt="brook-logo" />
          </li>

          <li class="col-2 text-center">
            <img src="../../assets/client-logo-04.png" alt="pencil-logo" />
          </li>

          <li class="col-2 text-center">
            <img src="../../assets/client-logo-05.png" alt="itsalive-logo" />
          </li>

          <li class="col-2 text-center">
            <img src="../../assets/client-logo-06.png" alt="sixbase-logo" />
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Download",
};
</script>

<style lang="scss">
@import "../../styles/download.scss";
</style>
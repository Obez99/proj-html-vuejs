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
            src="../assets/about-me-profile-ohm4dxoearqbxny7q3bq1pzbdgofdx0tobbeqcvzd0.jpg"
            alt=""
            class="rounded-circle"
          />
          <img
            src="../assets/maxcoach-shape-08.png"
            alt=""
            class="position-absolute fx1"
          />
          <img
            src="../assets/maxcoach-shape-08.png"
            alt=""
            class="position-absolute fx2"
          />

          <img
            src="../assets/maxcoach-shape-07-150x150.png"
            alt=""
            class="position-absolute fx3"
          />

          <img
            src="../assets/maxcoach-shape-02.png"
            alt=""
            class="position-absolute fx4"
          />
        </div>
      </div>

      <!--Clients section!-->
      <div class="clients-list mt-5">
        <ul class="row align-items-center">
          <li class="col-2 text-center">
            <img src="../assets/client-logo-01.png" alt="" />
          </li>

          <li class="col-2 text-center">
            <img src="../assets/client-logo-02.png" alt="" />
          </li>

          <li class="col-2 text-center">
            <img src="../assets/client-logo-03.png" alt="" />
          </li>

          <li class="col-2 text-center">
            <img src="../assets/client-logo-04.png" alt="" />
          </li>

          <li class="col-2 text-center">
            <img src="../assets/client-logo-05.png" alt="" />
          </li>

          <li class="col-2 text-center">
            <img src="../assets/client-logo-06.png" alt="" />
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "DownloadSection",
};
</script>

<style lang="scss">
.fx1,
.fx2,
.fx3,
.fx4 {
  z-index: -1;
}
.fx1 {
  left: 80px;
  top: 150px;
}

.fx2 {
  left: 80px;
  bottom: 150px;
}

.fx3 {
  bottom: 0;
  right: 80px;
}

.fx4 {
  top: 100px;
  right: -100px;
}
</style>
<template>
  <section style="position: relative; overflow: hidden">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-7">
          <div class="video-container">
            <img
              src="../../assets/icon-youtube-play.png"
              class="youtube-button"
              alt="play-video"
            />
            <img src="../../assets/maxcoach-shape-07.png" class="fx5" alt="" />
            <img src="../../assets/maxcoach-shape-05.png" class="fx6" alt="" />
            <svg
              xmlns="http://www.w3.org/2000/svg"
              version="1.1"
              width="200px"
              height="202px"
              viewBox="0 0 200 202"
              class="fx8"
            >
              <path
                class="elementor-shape-fill"
                d="M139.374493,198.087515 C155.702187,206.99353 190.724846,197.001323 197.677982,159.049528 C204.827153,120.027728 184.496324,118.997566 188.045232,104.801934 C202.287755,83.6528313 204.827153,56.662651 190.073179,40.4146034 C153.570125,2.39058926 144.444362,48.0194062 114.025151,20.1351292 C101.727304,7.83728238 83.0989526,-6.73517414 56.2286492,3.40456297 C18.2385839,17.7404371 27.3303985,47.659333 27.3303985,69.3128542 C27.3303985,76.9370868 3.11408002,91.2696589 0.460095291,110.885776 C-2.88628833,135.619549 12.6277797,168.175291 27.3303985,179.329002 C50.6517938,205.692318 86.6478605,199.608476 102.87144,190.482713 C116.802125,182.646702 128.220783,192.003673 139.374493,198.087515 Z"
              ></path>
            </svg>
            <div class="empty-circle fx9"></div>
          </div>
        </div>

        <div class="video-side col-4">
          <p>GET STARTED <strong>EFFORTLESSLY</strong></p>
          <h1>Enjoy Our <a href="#">Companionship</a></h1>
          <p>
            Sneek peek into what has in store for you on our online teaching and
            mentoring portal. Seek for some hidden hints of early-bird rewards
            as well.
          </p>
          <a href="#"
            >Download free guidebook <i class="fa fa-long-arrow-right"></i
          ></a>
        </div>
      </div>
    </div>
    <svg
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 100 100"
      preserveAspectRatio="none"
      height="315"
      class="wave"
    >
      <path class="elementor-shape-fill" d="M 50 0 S75 0 100 100 L100 0"></path>
    </svg>
  </section>
</template>

<script>
export default {
  name: "VideoSection",
};
</script>

<style lang="scss">
@import "../../styles/videosection.scss";
</style>
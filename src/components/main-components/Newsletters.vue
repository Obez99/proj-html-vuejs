<template>
  <section>
    <div class="container newsletters-container">
      <div class="row justify-content-center">
        <div class="col-6 text-center">
          <h2>Subscribe <a href="#">Newsletters</a></h2>
          <p>
            Enter your email address to register to our newsletter subscription
            delivered on a regular basis!
          </p>
          <form>
            <input type="email" placeholder="Enter your email" />
            <button type="submit" class="btn btn-primary">Subscribe</button>
          </form>
        </div>
      </div>

      <img src="../../assets/maxcoach-shape-09.png" class="fx6" alt="" />
      <img src="../../assets/maxcoach-shape-02.png" class="fx7" alt="" />
      <div class="empty-circle fx12"></div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Newsletters",
};
</script>

<style lang="scss">
@import "../../styles/newsletters.scss";
</style>
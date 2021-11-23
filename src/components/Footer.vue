<template>
  <footer>
    <div class="container">
      <div class="row">
        <!--Contacts!-->
        <div class="col-6">
          <h5>Address</h5>
          <ul>
            <li><p>382 NE 191st St # 87394 Miam, FL 33179-3899</p></li>
            <li><p>+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)</p></li>
            <li><p>support@maxcoach.com</p></li>
          </ul>
          <ul class="social-links">
            <li>
              <a href="#"><i class="fa fa-facebook-square"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-twitter"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-instagram"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-linkedin-square"></i></a>
            </li>
          </ul>
        </div>

        <!--Explore!-->
        <div class="col-3">
          <h5>Explore</h5>
          <ul class="explore-list">
            <li><a href="#">Start here</a></li>
            <li><a href="#">Success story</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Courses</a></li>
            <li><a href="#">About us</a></li>
            <li><a href="#">Contact us</a></li>
          </ul>
        </div>

        <!--Information!-->
        <div class="col-3">
          <h5>Information</h5>
          <ul>
            <li><a href="#">Membership</a></li>
            <li><a href="#">Purchase guide</a></li>
            <li><a href="#">Privacy policy</a></li>
            <li><a href="#">Terms of service</a></li>
          </ul>
        </div>
      </div>

      <p class="copyright-statement text-center">
        © 2020 Maxcoach. All Rights Reserved
      </p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss">
@import "../styles/footer.scss";
</style>
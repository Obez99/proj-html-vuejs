<template>
  <header>
    <div class="container">
      <img src="../assets/dark-logo.png" alt="logo" />

      <nav>
        <ul>
          <li>
            <a href="#">Home <i class="fa fa-chevron-down"></i></a>
          </li>
          <li>
            <a href="#">Pages <i class="fa fa-chevron-down"></i></a>
          </li>
          <li>
            <a href="#">Courses <i class="fa fa-chevron-down"></i></a>
          </li>
          <li>
            <a href="#">Features <i class="fa fa-chevron-down"></i></a>
          </li>
          <li>
            <a href="#">Blog <i class="fa fa-chevron-down"></i></a>
          </li>
          <li>
            <a href="#">Shop <i class="fa fa-chevron-down"></i></a>
          </li>
        </ul>

        <div>
          <a href="#"><i class="fa fa-user-o"></i></a>
          <input type="text" class="form-control" placeholder="Search..." />
          <i class="fa fa-search"></i>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss">
@import "../styles/header.scss";
</style>
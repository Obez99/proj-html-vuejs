<template>
  <div class="col-6">
    <h5>Address</h5>
    <ul>
      <li v-for="(item, i) in addressList" :key="i">
        <p>
          {{ item.content }}
          <span v-if="item.type === 'Phone'"
            >(9am - 5pm EST, Monday - Friday)</span
          >
        </p>
      </li>
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
</template>

<script>
export default {
  name: "Address",
  props: { addressList: Array },
};
</script>

<style>
</style>
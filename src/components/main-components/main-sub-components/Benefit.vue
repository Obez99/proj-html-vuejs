<template>
  <div class="col-3">
    <img :src="benefit.image" :alt="benefit.title" />

    <div class="benefit-description">
      <h3>{{ benefit.title }}</h3>
      <p>
        {{ benefit.description }}
      </p>
      <a :href="benefit.linkRef"
        >{{ benefit.linkText }} <i class="fa fa-long-arrow-right"></i
      ></a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Benefit",
  props: { benefit: Object },
};
</script>

<style>
</style>
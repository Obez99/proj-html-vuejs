<template>
  <div class="review-card" :class="review.active ? 'active' : ''">
    <h5>{{ review.title }}</h5>
    <p>{{ review.description }}</p>

    <!--Card author!-->
    <div class="review-author">
      <img :src="review.author.photo" :alt="review.author.name" />
      <div class="author-info">
        <h6 class="text-uppercase">{{ review.author.name }}</h6>
        <small>/ {{ review.author.role }}</small>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Review",
  props: { review: Object },
};
</script>

<style>
</style>
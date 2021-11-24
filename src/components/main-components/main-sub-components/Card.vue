<template>
  <div class="col-3 insight-card">
    <img :src="card.image" :alt="card.title" />
    <div class="insight-card-body">
      <p>ARTIST</p>
      <h5>{{ card.title }}</h5>
      <span><i class="fa fa-calendar-o"></i>{{ card.date }}</span>
      <span><i class="fa fa-eye"></i>{{ card.views }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: { card: Object },
};
</script>

<style>
</style>
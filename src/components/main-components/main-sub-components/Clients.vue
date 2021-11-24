<template>
  <div class="clients-list mt-5">
    <ul class="row align-items-center">
      <li v-for="(client, i) in clientsList" :key="i" class="col-2 text-center">
        <img :src="client.image" :alt="client.name" />
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Clients",
  props: { clientsList: Array },
};
</script>

<style>
</style>
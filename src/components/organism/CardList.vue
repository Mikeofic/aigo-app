<script setup>
import CategoryCard from '../molecule/CategoryCard.vue';


</script>

<template>
  <div class="card-list">
    <CategoryCard />
    <CategoryCard />
  </div>
</template>


<style scoped lang="scss">
  .card-list {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 24px;

    width: 100%;
  }
</style>

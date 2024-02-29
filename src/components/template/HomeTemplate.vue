<template>
  <div class="container">
    <CardList />
  </div>
</template>

<script setup>
import CardList from '../organism/CardList.vue';


</script>

<style lang="scss" scoped>
  .container {
    width: 100%;
    height: 100%;
    background-color: var(--grey-100);
    border-radius: 8px;

    display: flex;
    flex-direction: row;
    justify-content: center;
  }
</style>

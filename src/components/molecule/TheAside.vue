<script setup>

</script>

<template>
  <div class="aside">
    <h2>Minhas Sprints</h2>
    <hr>

    <div class="sprints__list">
      <ul>
        <li>Sprint #01</li>
        <li>Sprint #02</li>
        <li>Sprint #03</li>
        <li>Sprint #04</li>
        <li>Sprint #05</li>
        <li>Sprint #06</li>
        <li>Sprint #01</li>
        <li>Sprint #02</li>
        <li>Sprint #03</li>
        <li>Sprint #04</li>
        <li>Sprint #05</li>
        <li>Sprint #06</li>
      </ul>
    </div>

  </div>
</template>

<style scoped lang="scss">
.aside {
  .sprints__list {
    padding: 1.5rem;

    li {
      margin-bottom: 16px;
      cursor: pointer;
      padding: 4px 8px;
      border-radius: 8px;
      background-color: var(--grey-200);
    }
  }

  hr {
    margin: 16px 0;
  }
}

</style>

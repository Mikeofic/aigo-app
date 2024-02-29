<script setup>

</script>

<template>
  <section class="card">
    <h1> Card</h1>
      <ul>
        <li>Tarefa</li>
        <li>Tarefa</li>
        <li>Tarefa</li>
        <li>Tarefa</li>
        <li>Tarefa</li>
        <li>Tarefa</li>
      </ul>
  </section>
</template>


<style scoped lang="scss">
  .card {
    width: 100%;
    max-width: 300px;
    height: 600px;
    background-color: antiquewhite;
    border-radius: 8px 8px 45px 8px;

    padding: 1.5rem;

    box-shadow: 0px 10px 15px -5px rgba(0,0,0,0.5);

    h1 {
      margin-bottom: 32px;
    }

    ul {
      margin-left: 24px;

      li + li {
        margin-top: 16px;
      }
    }
  }
</style>

<script setup>
import TheAside from '@/components/molecule/TheAside.vue';
import TheHeader from './components/molecule/TheHeader.vue';
import HomeView from './views/HomeView.vue';
import TheFooter from './components/molecule/TheFooter.vue';
</script>

<template>
  <header>
    <TheHeader />
  </header>

  <aside>
    <TheAside />
  </aside>

  <main>
    <HomeView />
  </main>

  <footer>
    <TheFooter />
  </footer>
</template>

<style lang="scss">

header {
  grid-area: header;
  background-color: #333;
  box-shadow: 0px 10px 15px -5px rgba(0,0,0,0.5);
  color: white;
  padding: 1rem;
}

aside {
  grid-area: aside;
  background-color: #ddd;
  padding: 1rem;
  box-shadow: 0px 10px 15px -5px rgba(0,0,0,0.5);
}

main {
  grid-area: main;
  padding: 1rem;
}

footer {
  grid-area: footer;
  background-color: #333;
  color: white;
  padding: 1rem;
}



#app {
  font-family: "Fira Code", monospace;
  font-optical-sizing: auto;
  font-style: normal;
  background-color: rgb(179, 235, 235);

  display: grid;
  grid-template-columns: 1fr 3fr;
  grid-template-rows: auto 1fr auto;
  grid-template-areas:
    "header header"
    "aside main"
    "footer footer";
  min-height: 100vh;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

a, li, ol {
  text-decoration: none;
}

body {
}
</style>

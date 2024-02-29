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
  background-color: var(--grey-400);
  box-shadow: 0px 10px 15px -5px rgba(0,0,0,0.5);
  color: white;
  padding: 1rem;
}

aside {
  grid-area: aside;
  background-color: var(--grey-100);
  padding: 1rem;
  box-shadow: 0px 10px 15px -5px rgba(0,0,0,0.5);
}

main {
  grid-area: main;
  padding: 1rem;
}

footer {
  grid-area: footer;
  background-color: var(--grey-400);
  color: white;
  padding: 1rem;
}



#app {
  font-family: "Fira Code", monospace;
  font-optical-sizing: auto;
  font-style: normal;
  background-color: var(--grey-100);

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

:root {
  --grey-100: #F2F2F2;
  --grey-200: #A6A6A6;
  --grey-300: #595959;
  --grey-400: #262626;
  --grey-500: #0D0D0D;
}
</style>

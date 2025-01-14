<script setup lang="ts">
import Header from "./components/Header.vue";
import Einleitung from "./components/Einleitung.vue";
import Mitmachen from "./components/Mitmachen.vue";
import Solawi from "./components/Solawi.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div id="app">
    <Header />
    <main class="content">
      <Einleitung msg="hi =)"></Einleitung>
      <Mitmachen></Mitmachen>
      <Solawi></Solawi>
    </main>
    <Footer />
  </div>
</template>

<style scoped>
#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.content {
  flex: 1;
  padding-bottom: 60px; /* Prevents content from hiding behind the footer */
}
</style>

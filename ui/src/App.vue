<script setup>
import Navbar from "./components/Navbar.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <Navbar />
  <Main />
  <Footer />
</template>

<style scoped>
* {
  width: 100%;
  margin: auto;
  padding: 0;
}

.app {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>

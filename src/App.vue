<template>
  <div>
    <navbar />
    <div>
      <hero />
    </div>
    <div>
      <about />
      <portfolio />
    </div>
  </div>
</template>

<script setup>
import hero from "./components/hero.vue";
import navbar from "./components/navbar.vue";
import about from "./components/about.vue";
import portfolio from "./components/portfolio.vue";

</script>

<style scoped></style>

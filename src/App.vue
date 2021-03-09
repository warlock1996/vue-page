<template>
  <div id="app">
    <div class="header">
      <top-bar />
      <hero-section />
      <movement />
    </div>
    <div class="content"></div>
    <div class="footer"></div>
  </div>
</template>

<script>
import TopBar from "./components/TopBar.vue";
import HeroSection from "./components/HeroSection.vue";
import Movement from "./components/Movement.vue";
export default {
  name: "App",
  components: {
    TopBar,
    HeroSection,
    Movement,
  },
};
</script>

<style scoped></style>

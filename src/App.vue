<template>
  <div id="app">
    <div class="header">
      <top-bar />
      <hero-section />
      <movement-section />
      <join-section />
      <features-section />
    </div>
    <div class="content"></div>
    <div class="footer"></div>
  </div>
</template>

<script>
import TopBar from "./components/TopBar.vue";
import HeroSection from "./components/HeroSection.vue";
import MovementSection from "./components/MovementSection.vue";
import JoinSection from "./components/JoinSection.vue";
import FeaturesSection from "./components/FeaturesSection.vue";
export default {
  name: "App",
  components: {
    TopBar,
    HeroSection,
    MovementSection,
    JoinSection,
    FeaturesSection,
  },
};
</script>

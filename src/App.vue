<template>
  <div id="app">
    <div class="header">
      <top-bar />
      <hero-section />
      <movement-section />
      <join-section />
      <features-section />
      <movement-card />
      <Footer></Footer>
    </div>
    <div class="content"></div>
  </div>
</template>

<script>
import TopBar from "./components/TopBar.vue";
import HeroSection from "./components/HeroSection.vue";
import MovementSection from "./components/MovementSection.vue";
import JoinSection from "./components/JoinSection.vue";
import FeaturesSection from "./components/FeaturesSection.vue";
import MovementCard from "./components/MovementCard.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    TopBar,
    HeroSection,
    MovementSection,
    JoinSection,
    FeaturesSection,
    MovementCard,
    Footer,
  },
};
</script>

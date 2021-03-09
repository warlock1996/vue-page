<template>
  <div id="app">
    <header>
      <top-bar />
      <hero-section />
    </header>
    <section>
      <movement-section />
      <join-section />
      <features-section />
      <movement-card />
      <video-section />
    </section>
    <Bar />
    <footer>
      <Footer></Footer>
    </footer>
  </div>
</template>

<script>
import TopBar from "./components/TopBar.vue";
import HeroSection from "./components/HeroSection.vue";
import MovementSection from "./components/MovementSection.vue";
import JoinSection from "./components/JoinSection.vue";
import FeaturesSection from "./components/FeaturesSection.vue";
import MovementCard from "./components/MovementCard.vue";
import VideoSection from "./components/VideoSection.vue";
import Bar from "./components/Bar.vue";
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
    VideoSection,
    Bar,
    Footer,
  },
};
</script>

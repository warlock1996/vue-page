<template>
  <div id="app">
    <header>
      <top-bar />
      <hero-section />
    </header>
    <section>
      <movement-section />
      <join-section />
      <feedback-carousel />
      <features-section />
      <video-section />
      <Bar />
      <media-carousel></media-carousel>
    </section>
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
import MediaCarousel from "./components/MediaCarousel.vue";
import FeedbackCarousel from "./components/FeedbackCarousel.vue";
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
    MediaCarousel,
    FeedbackCarousel,
    Bar,
    Footer,
  },
};
</script>

<style lang="scss">
@use './assets/scss/_mixins.scss' as *;

.vueperslides__arrow {
  border: 3px solid var(--primary-clr);
  border-radius: 50px;
  @include gradient-one;
  svg {
    width: 50px;
    height: 60px;
  }
}

.vueperslides__arrow--prev {
  left: 3rem;
}
.vueperslides__arrow--next {
  right: 3rem;
}

.join--section {
  div.vueperslide {
    &__content-wrapper {
      color: var(--primary-clr);
      font-size: var(--fs-lg);
      margin-top: -20px !important;
      justify-content: flex-end !important;
    }
  }
}

.feedback--carousel {
  .vueperslides__track {
    overflow: visible;
  }
  .vueperslide__content {
    background-color: var(--primary-clr);
    border-radius: 10px;
    box-shadow: 0px 0px 1px 1px var(--section-bg-clr-light);
    font-size: var(--fs-sm);
    padding: 20px;
    opacity: var(--opacity);
    text-align: left;
    transition: transform 1s;
  }
  .vueperslide--active {
    .vueperslide__content {
      transform: scale(1.2);
    }
  }
}
</style>

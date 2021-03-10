<template>
  <b-container fluid class="feedback--carousel">
    <h1 class="feedback--carousel--title text-center">
      HEAR WHAT OUR CUSTOMERS SAY!
    </h1>
    <vueper-slides
      class="no-shadow "
      :visible-slides="3"
      :slide-ratio="1 / 4"
      :gap="4"
      :dragging-distance="70"
      :bullets="false"
      :arrows-outside="false"
    >
      <vueper-slide
        class="text-left"
        v-for="i in 6"
        :key="i"
        :content="content"
      />
    </vueper-slides>
    <b-button class="read-btn d-block mx-auto mt-4"
      >Read More Testimonials</b-button
    >
  </b-container>
</template>

<script>
import { VueperSlides, VueperSlide } from "vueperslides";
import "vueperslides/dist/vueperslides.css";
export default {
  components: {
    VueperSlides,
    VueperSlide,
  },
  data() {
    return {
      content: `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.`,
    };
  },
};
</script>

<style lang="scss" scoped>
.feedback--carousel {
  padding: 20px;
  background-image: url("../assets/images/BG.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  &--title {
    font-size: var(--fs-lg);
    color: var(--primary-clr);
  }
}
.read-btn {
  background-image: none;
  border: 1px solid var(--primary-clr);
  background-color: var(--section-bg-clr);
}
</style>

<template>
  <b-container fluid class="media--section p-4">
    <h1 class="media--section--title text-center mb-4">As Seen On</h1>
    <vueper-slides
      class="media--section--carousel no-shadow"
      :visible-slides="4"
      slide-multiple
      :gap="0.1"
      :slide-ratio="1 / 3"
      :dragging-distance="200"
      :bullets="false"
      :arrows-outside="false"
      fixed-height="180px"
    >
      <vueper-slide v-for="i in 5" :key="i">
        <template v-slot:content>
          <b-img :src="require(`../assets/images/media (${i + 1}).png`)">
          </b-img>
        </template>
      </vueper-slide>
    </vueper-slides>
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
};
</script>

<style lang="scss" scoped>
.media--section {
  background-color: var(--section-bg-clr-light);
  &--title {
    color: var(--primary-clr);
    font-size: var(--fs-lg);
  }
}
</style>

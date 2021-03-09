<template>
  <vueper-slides
    class="no-shadow"
    :visible-slides="5"
    slide-multiple
    :gap="1"
    :slide-ratio="1 / 4"
    :dragging-distance="200"
    :bullets="false"
    :arrows-outside="false"
  >
    <vueper-slide
      v-for="i in 5"
      :key="i"
      :image="require(`../assets/images/media (${i}).png`)"
    />
  </vueper-slides>
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

<style></style>

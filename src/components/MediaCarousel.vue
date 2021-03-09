<template>
  <vueper-slides
    class="no-shadow"
    :visible-slides="5"
    slide-multiple
    :gap="2"
    :slide-ratio="1 / 4"
    :dragging-distance="200"
    :bullets="false"
    :arrows-outside="false"
  >
    <vueper-slide v-for="i in 5" :key="i">
      <template v-slot:content>
        <b-img :src="require(`../assets/images/media (${i + 1}).png`)"> </b-img>
      </template>
    </vueper-slide>
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

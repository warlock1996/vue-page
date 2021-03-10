<template>
  <vueper-slides
    class="no-shadow"
    :visible-slides="4"
    slide-multiple
    :gap="1"
    :slide-ratio="1 / 4"
    :dragging-distance="200"
    :bullets="false"
    :arrows-outside="false"
  >
    <vueper-slide
      class="join__carousel__slide"
      v-for="i in 5"
      :key="i"
      :title="titles[i - 1]"
      :image="require(`../assets/images/${i}.png`)"
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
  data() {
    return {
      titles: ["PROFESSIONALS", "WOMAN", "MEN", "SENIOR", "CHILDRENS"],
    };
  },
};
</script>

<style lang="scss" scoped></style>

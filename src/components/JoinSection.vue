<template>
  <b-container class="join--section" fluid>
    <b-row>
      <b-col>
        <h1 class="join--section--title text-center">
          Think it's not for you? Think again!
        </h1>
      </b-col>
    </b-row>
    <b-row>
      <b-col md="12">
        <join-carousel />
        <h1 class="join--section--bottom--text text-center">
          JOIN THE MOVEMENT
        </h1>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <b-img
          class="join--section--bottom--image mx-auto d-block"
          :src="require('../assets/images/arrow.png')"
          alt="Fluid image"
        ></b-img>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import JoinCarousel from "./JoinCarousel";
import MovementCard from "./MovementCard";
export default {
  components: {
    JoinCarousel,
    MovementCard,
  },
};
</script>

<style lang="scss" scoped>
@use '../assets/scss/_mixins.scss' as *;

.join--section {
  position: relative;
  background-color: var(--section-bg-clr-light);
  &--title {
    color: var(--secondary-clr);
  }
  &--bottom--image {
    margin: {
      top: 50px;
      bottom: 50px;
    }
    padding: 10px;
  }
  &--bottom--text {
    @include gradient-one;
    padding: 20px;
    width: 100%;
    position: absolute;
    bottom: -80px;
    left: 0px;
    color: var(--primary-clr);
  }
}
</style>

<template>
  <b-container fluid>
    <b-row>
      <b-col>
        <h1 class="text-center">Think it's not for you? Think again!</h1>
      </b-col>
    </b-row>
    <b-row>
      <b-col md="12">
        <join-carousel />
        <h1 class="text-center">JOIN THE MOVEMENT</h1>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <b-img
          class="mx-auto d-block"
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
<style lang="scss" scoped></style>

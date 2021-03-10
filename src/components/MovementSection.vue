<template>
  <b-container fluid class="movement--section p-4 px-5">
    <b-row>
      <b-col>
        <h1 class="movement--section--title mb-4 text-center">
          JOIN THE MOVEMENT
        </h1>
      </b-col>
    </b-row>
    <b-row>
      <b-col md="6">
        <movement-card
          card-text="WE HAVE THE PRODUCT"
          card-btn-text="BUY TODAY"
        />
      </b-col>
      <b-col md="6">
        <movement-card
          card-text="AND PROVIDE THE TRAINING"
          card-btn-text="TRAIN NOW"
        />
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <b-img
          class="mx-auto mt-5 d-block"
          :src="require('../assets/images/arrow.png')"
          alt="Fluid image"
        ></b-img>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import MovementCard from "./MovementCard";
export default {
  components: {
    MovementCard,
  },
};
</script>
<style lang="scss" scoped>
.movement--section {
  background-color: var(--section-bg-clr);
  &--title {
    color: var(--primary-clr);
  }
}
</style>

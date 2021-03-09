<template>
  <b-card
    class="border-0"
    body-class="p-0 movement--card d-flex flex-column align-items-center justify-content-around"
  >
    <div class="movement--card--image--text">{{ cardText }}</div>
    <b-img
      class="movement--card--image"
      fluid
      :src="require('../assets/images/23.jpg')"
    >
    </b-img>
    <b-button class="movement--card--image--button">{{ cardBtnText }}</b-button>
  </b-card>
</template>

<script>
export default {
  props: ["cardText", "cardBtnText"],
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.movement--card {
  width: 100%;
  position: relative;
  &--image--text {
    position: absolute;
    top: 10px;
  }
  &--image--button {
    position: absolute;
    bottom: 40px;
  }
}
</style>

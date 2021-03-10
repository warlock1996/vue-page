<template>
  <b-container fluid class="d-flex flex-column hero--section">
    <b-row class="hero--section--navbar">
      <b-col>
        <nav-bar />
      </b-col>
    </b-row>
    <b-row
      class="hero--section--content text-center flex-column align-self-center"
    >
      <b-col>
        <h1 class="hero--section--content--title mx-auto">
          WHY WORK <i>OUT...</i> WHEN YOU CAN <i><u>PLAY IN!</u></i>
        </h1>
      </b-col>
      <b-col>
        <b-button>BUY NOW</b-button>
      </b-col>
      <b-col>
        <b-img
          :src="require('../assets/images/arrow.png')"
          alt="Fluid image"
        ></b-img>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import NavBar from "./NavBar.vue";
export default {
  components: {
    NavBar,
  },
};
</script>

<style lang="scss" scoped>
.hero--section {
  height: 600px;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("../assets/images/BG.png");

  &--content {
    &--title {
      width: 60%;
      color: var(--primary-clr);
      font-size: var(--fs-xl);
      i {
        color: var(--secondary-clr);
      }
    }
  }
  &--navbar {
    flex-grow: 0.5;
  }
  &--content {
    flex-grow: 0.2;
  }
}
</style>

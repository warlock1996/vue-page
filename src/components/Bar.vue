<template>
  <div class="bar--section">
    <h1 class="bar--section--title text-center">
      REACH YOUR GREATER HEALTH POTENTIAL
    </h1>
    <b-img
      class="d-block mx-auto my-4"
      :src="require('../assets/images/arrow.png')"
    ></b-img>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@use '../assets/scss/_mixins.scss' as *;

.bar--section {
  &--title {
    @include gradient-one;
    padding: 20px;
    color: var(--primary-clr);
  }
}
</style>

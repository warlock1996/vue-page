<template>
  <b-container fluid class="video--section--container">
    <b-row align-h="between">
      <b-col>
        <h1>CELLERCISE IF FOR EVERY PART OF YOUR BODY</h1>
      </b-col>
      <b-col>
        <div class="d-flex justify-content-end align-items-center">
          <b-icon-arrow-left-short></b-icon-arrow-left-short>
          <b-img :src="require('../assets/images/8.png')"></b-img>
          <b-img :src="require('../assets/images/9.png')"></b-img>
          <b-img :src="require('../assets/images/10.png')"></b-img>
          <b-icon-arrow-right-short></b-icon-arrow-right-short>
        </div>
      </b-col>
    </b-row>
    <b-row align-h="between">
      <b-col class="text-left position-relative">
        <b-img :src="require('../assets/images/22.png')"></b-img>
        <span class="text-spanner position-absolute">
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book.
        </span>
      </b-col>
      <b-col class="text-right">
        <b-img :src="require('../assets/images/11.png')"></b-img>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.video--section--container {
  min-height: 900px;
  background-image: url("../assets/images/7.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
}
.text-spanner {
  top: 50px;
  left: 50px;
  width: 400px;
}
</style>

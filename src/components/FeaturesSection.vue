<template>
  <b-container class="features--section p-5" fluid>
    <b-row class="align-items-start justify-content-center">
      <b-col md="3">
        <b-img
          class="features--section--image"
          :src="require('../assets/images/18.png')"
        ></b-img>
        <h1 class="features--section--item--title">HEART HEALTHY</h1>
        <p>
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book.
        </p>
      </b-col>
      <b-col md="3">
        <b-img
          class="features--section--image"
          :src="require('../assets/images/19.png')"
        ></b-img>
        <h1 class="features--section--item--title">TRI DATATABLE SPRING</h1>
        <p>
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book.
        </p>
      </b-col>
      <b-col md="3">
        <b-img
          class="features--section--image"
          :src="require('../assets/images/20.png')"
        ></b-img>
        <h1 class="features--section--item--title">FOLDABLE DESIGN</h1>
        <p>
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book.
        </p>
      </b-col>
      <b-col md="3">
        <b-img
          class="features--section--image"
          :src="require('../assets/images/21.png')"
        ></b-img>
        <h1 class="features--section--item--title">STEEL CONSTRUCTION</h1>
        <p>
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book.
        </p>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.features--section {
  background-color: var(--primary-clr);
  &--item--title {
    color: var(--secondary-clr);
    font-size: var(--fs-lg);
  }
  &--image {
    margin-bottom: 10px;
  }
}
</style>

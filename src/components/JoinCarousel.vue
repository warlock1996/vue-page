<template>
  <b-carousel
    id="carousel-1"
    :interval="100000"
    controls
    background="#ababab"
    img-width="900"
    img-height="1200"
  >
    <b-carousel-slide
      caption="SENIOR"
      img-width="308"
      img-height="374"
      :img-src="require('../assets/images/4.png')"
    ></b-carousel-slide>
    <b-carousel-slide
      img-width="308"
      img-height="374"
      caption="WOMAN"
      :img-src="require('../assets/images/2.png')"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="MEN"
      :img-src="require('../assets/images/3.png')"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="PROFESSIONALS"
      :img-src="require('../assets/images/1.png')"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Children"
      :img-src="require('../assets/images/5.png')"
    ></b-carousel-slide>
  </b-carousel>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
    };
  },
  mounted() {
    document.querySelector(".carousel-inner").style.display = "flex";
    // element.setAttribute('class', '')
  },
};
</script>

<style lang="scss" scoped>
#carousel-1 >>> .carousel-inner {
  width: 120%;
}
#carousel-1 {
  .carousel-inner {
    width: 120%;
    .carousel-item {
      display: flex;
      margin-right: 0px;
      float: left;
      width: fit-content;
    }
  }
}
</style>

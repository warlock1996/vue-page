<template>
  <b-navbar toggleable="md" type="light">
    <b-navbar-brand href="#">
      <b-img
        :src="require('../assets/images/Cellercise Logo.png')"
        alt="Fluid image"
      ></b-img>
    </b-navbar-brand>

    <b-navbar-toggle target="top-collapse"></b-navbar-toggle>

    <b-collapse id="top-collapse" is-nav>
      <b-navbar-nav class="mx-auto">
        <b-nav-item href="#"
          >BEST DEALS ON REBOUNDERS-<span>25% OFF</span></b-nav-item
        >
      </b-navbar-nav>

      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#"
          ><b-img
            :src="require('../assets/icons/facebook.png')"
            alt="Fluid image"
          ></b-img
        ></b-nav-item>
        <b-nav-item href="#"
          ><b-img
            :src="require('../assets/icons/instagram.png')"
            alt="Fluid image"
          ></b-img
        ></b-nav-item>
        <b-nav-item href="#"
          ><b-img
            :src="require('../assets/icons/pintrest.png')"
            alt="Fluid image"
          ></b-img
        ></b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {};
</script>

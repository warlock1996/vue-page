<template>
  <b-navbar toggleable="md" type="light">
    <b-navbar-toggle class="ml-auto" target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="HOME">HOME</b-nav-item>
        <b-nav-item href="SHOP">SHOP</b-nav-item>
        <b-nav-item href="BENEFITS">BENEFITS</b-nav-item>
        <b-nav-item href="ABOUT">ABOUT</b-nav-item>
        <b-nav-item href="EXERCISES">EXERCISES</b-nav-item>
        <b-nav-item href="CONTACT">CONTACT US</b-nav-item>
      </b-navbar-nav>

      <b-navbar-nav class="ml-auto align-items-center">
        <b-nav-item href="#"
          ><b-img
            :src="require('../assets/icons/cart.png')"
            alt="Fluid image"
          ></b-img
        ></b-nav-item>
        <b-nav-item href="#"
          ><b-img
            :src="require('../assets/icons/magnify.png')"
            alt="Fluid image"
          ></b-img
        ></b-nav-item>
        <b-nav-item href="#">
          <b-button>LOGIN</b-button>
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.navbar {
  &-collapse {
    ul {
      li {
        a.nav-link {
          color: var(--primary-clr);
          &:hover,
          &:active {
            color: var(--secondary-clr);
          }
        }
      }
    }
  }
}
</style>

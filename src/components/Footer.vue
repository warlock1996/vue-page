<template>
  <b-container fluid class="footer--section">
    <b-row class="p-5">
      <b-col cols="4">
        <div>
          <img src="../assets/images/Cellercise Logo.png" alt="" />
        </div>
        <h4 class="mt-4">
          The Cellercise&reg; Brand
        </h4>
        <p class="mt-3">
          Cellercise&reg;, Cellerciser&reg; and Cellology&reg;, The TriDaptable
          <br />
          Spring&reg; and the MrRebounder&trade; program are copyrighted <br />
          as the exclusive intellectual property of David Hall and <br />
          Health and Beyond LLC. All rights reserved.
        </p>
        <b-button class="mt-5">BECOME AN AFFILIATE</b-button>
        <h6 class="mt-5">
          <span>&#169;</span> 2020 Copyright Cellercise&reg;. All Rights
          Reserved
        </h6>
      </b-col>
      <b-col cols="3">
        <h5>Additional Links</h5>
        <p class="mt-4 mb-0">My Account</p>
        <p class="mb-0">Cellercise&reg; Disclaimer</p>
        <p class="mb-0">Warrenty</p>
        <p class="mb-0">Return Policy</p>
        <p class="mb-0">Terms of Service</p>
        <p class="mb-0">Privacy Statement</p>
        <p class="mb-0">Become an Affiliate</p>
      </b-col>
      <b-col cols="5">
        <h5>Sign up to receive important updates!</h5>
        <b-form class="mt-4" action="" inline>
          <b-form-input
            id="inline-form-input-name"
            class="mb-2 mr-sm-2 mb-sm-0"
            placeholder="Name"
          >
          </b-form-input>
          <b-form-input
            id="inline-form-input-name"
            class="mb-2 mr-sm-2 mb-sm-0"
            placeholder="Email"
          >
          </b-form-input>
        </b-form>
        <h5 class="mt-3">Get in Touch!</h5>

        <div class="d-flex align-items-start">
          <b-icon-telephone-fill></b-icon-telephone-fill>
          <span class="ml-3">
            87 N. Manti St. <br />
            Manti, Utah 84642
          </span>
        </div>
        <div class="d-flex align-items-start">
          <b-icon-telephone-fill></b-icon-telephone-fill>
          <span class="ml-3">
            Toll-Free: 800-856-4863 <br />
            International: 435-562-4456
          </span>
        </div>
        <div class="d-flex align-items-start">
          <b-icon-clock-fill></b-icon-clock-fill>
          <span class="ml-3">
            Monday - Friday 9AM-5PM MST
          </span>
        </div>
        <div class="d-flex align-items-start">
          <b-icon-envelope></b-icon-envelope>
          <span class="ml-3">
            info@cellercise.com
          </span>
        </div>

        <!-- Toll-Free: 800-856-4863
International: 435-562-4456

Monday - Friday 9AM-5PM MST

info@cellercise.com -->
      </b-col>
    </b-row>
  </b-container>
</template>

<style lang="scss" scoped>
.footer--section {
  min-height: 600px;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("../assets/images/Footer.png");
}
</style>

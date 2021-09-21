<template>
    <div class="container mt-3 height">
      <div class="row justify-content-center">
          <div class="col-11 col-md-8 col-lg-6 px-0">
            <hero-image class="px-0 rounded-3" ></hero-image>
          </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-11 col-md-8 col-lg-6 bg-white py-2 rounded-bottom">
          <order-summary class=""></order-summary>
        </div>
      </div>
    </div>
</template>

<script>
import HeroImage from './components/HeroImage.vue'
import OrderSummary from './components/summary/orderSummary.vue'

export default {
  components: {
    HeroImage,
    OrderSummary
  }
}
</script>

<style>
body {
  background-color: hsl(225, 100%, 94%);
}
.height {
  max-height: 100vh;
}
</style>

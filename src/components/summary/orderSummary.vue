<template>
  <h3 class="text-center">Order Summary</h3>
  <p class="text-center">
    You can now listen to millions of songs, audiobooks, and podcasts on any
    device anywhere you like!
  </p>
  <div class="row">
    <div class="col">
      <div class="card plan">
        <div class="card-body">
          <div class="row">
            <div class="col-2">
                <img src="../../assets/icon-music.svg" alt="" class="img-fluid">
            </div>
            <div class="col">
              <h5 class="card-title">Annual Plan</h5>
              <p class="text-muted">$59.99/year</p>
            </div>
            <div class="col py-2 text-end">
              <a href="#" class="fw-bold change">Change</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="row mt-2">
      <div class="col-12">
            <a class="btn payment d-block rounded text-white">Proceed to Payment</a>
        </div>
  </div>
  <div class="row mt-2">
      <div class="col-12">
            <a class="btn cancel d-block rounded">Cancel Order</a>
        </div>
  </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.plan {
    background-color: hsl(225, 100%, 98%);
    max-height: 14vh;
}
.change {
  color: hsl(245, 75%, 52%);
}
a:hover {
    text-decoration: none;
}
.payment {
    background-color: hsl(245, 75%, 52%);
}
.cancel {
  color:    hsl(224, 23%, 55%);
}
</style>
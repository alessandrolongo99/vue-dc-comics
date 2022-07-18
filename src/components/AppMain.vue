<template>
  <div class="container-bg-dark">
    <div class="jumbo">
      <div class="container position-relative">
        <div
          class="
            floating-text
            text-white text-uppercase
            fs-3
            fw-bold
            px-4
            py-2
            position-absolute
          "
        >
          current series
        </div>
      </div>
    </div>
    <div class="container fs-1 text-white">
      <AppProducts />
    </div>
    <div class="buy-products py-5">
      <div class="container">
        <div class="row d-flex align-items-center justify-content-between">
          <div class="col-2">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital-comics">
            <span class="text-uppercase text-white">digital comics</span>
          </div>
          <div class="col-2">
            <img src="../assets/img/buy-comics-merchandise.png" alt="buy-comics-merchandise">
            <span class="text-uppercase text-white">dc merchandise</span>
          </div>
          <div class="col-2">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="buy-comics-subscriptions">
            <span class="text-uppercase text-white">subscription</span>
          </div>
          <div class="col-2">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="buy-comics-shop-locator">
            <span class="text-uppercase text-white">comic shop locator</span>
          </div>
          <div class="col-2">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="buy-dc-power-visa">
            <span class="text-uppercase text-white">dc power visa</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AppProducts from "./AppProducts.vue";

export default {
  name: "AppMain",
  components: {
    AppProducts,
  },
};
</script>

<style scoped>
.container-bg-dark {
  background-color: #1c1c1c;
}

.container {
  padding: 0;
}

.jumbo {
  background-image: url("../assets/img/jumbotron.jpg");
  background-size: cover;
  height: 400px;
}

.jumbo > div {
  height: 100%;
}

.floating-text {
  background-color: #0282f9;
  bottom: 0;
  transform: translate(0, 50%);
}

.buy-products {
  background-color: #0282f9;
}

img{
  height: 40px;
}

span{
  padding-left: 5px;
}
</style>
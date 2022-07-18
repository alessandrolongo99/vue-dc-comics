<template>
  <div class="container-bg-dark">
    <div class="jumbo">
      <div class="container position-relative">
        <div class="floating-text text-white text-uppercase fs-3 fw-bold px-4 py-2 position-absolute">current series</div>
      </div>
    </div>
    <div class="container fs-1 text-white">
      <AppProducts/>
    </div>
  </div>
</template>

<script>
import AppProducts from './AppProducts.vue'

export default {
  name: 'AppMain',
  components: {
    AppProducts,
  }
};
</script>

<style scoped>
.container-bg-dark{
  background-color: #1c1c1c;
}

.container {
  padding: 4rem 0;
}

.jumbo{
  background-image: url('../assets/img/jumbotron.jpg');
  background-size: cover;
  height: 400px;
}

.jumbo > div{
  height: 100%;
}

.floating-text{
  background-color: #0282f9;
  bottom: 0;
  transform: translate(0, 50%);
}
</style>
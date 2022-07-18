<template>
  <div class="product-card col-2 mt-5">
    <div class="img-container">
      <img :src="imageSrc" :alt="productSeries" />
    </div>
    <h6 class="mt-2">{{ productSeries }}</h6>
  </div>
</template>

<script>
export default {
  props: {
    imageSrc: String,
    productPrice: String,
    productSeries: String,
    productType: String,
  },
};
</script>

<style scoped lang="scss">
.img-container{
    height: 200px;
    width: 200px;
}

img {
    display: inline-block;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: top;
}
</style>
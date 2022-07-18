<template>
  <div class="product-card">
    <img :src="imageSrc" :alt="productSeries">
    <h4>{{productSeries}}</h4>
  </div>
</template>

<script>
export default {
    props: {
        'imageSrc': String,
        'productPrice': String,
        'productSeries': String,
        'productType': String,
    }
}
</script>

<style>

</style>
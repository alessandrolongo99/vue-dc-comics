<template>
  <div class="container-bg-dark">
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
</style>
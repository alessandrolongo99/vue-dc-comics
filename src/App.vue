<template>
  <div id="app">
    <AppHeader/>
    <AppMain/>
    <AppFooter/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppProducts from './components/AppProducts.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppProducts,
    AppFooter,
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";

</style>

<template>
  <div id="app">
    <AppHeader/>
    <AppMain/>
    <AppFooter/>
    <FooterBar/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppProducts from './components/AppProducts.vue';
import FooterBar from './components/FooterBar.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppProducts,
    AppFooter,
    FooterBar,
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";

</style>

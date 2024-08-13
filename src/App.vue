<template>
  <div id="app">
      <div>
    <div class="title-logo">
      <img class="logo" alt="logo" src="./assets/LogoO.png">Interno
      <CompHeader/>
      <ProductDetails/>
      <CompFooter/>
    </div>
  </div>
  </div>
</template>

<script>

import CompFooter from './components/CompFooter.vue';
import CompHeader from './components/CompHeader.vue';
import ProductDetails from './components/ProductDetails.vue';


export default {
  name: 'App',
  components: {
    CompHeader,
    CompFooter,
    ProductDetails,
  }
}
</script>

<style>
.logo {
  width: 30px;
}

.title-logo {
  font-size: 30px;
}

</style>

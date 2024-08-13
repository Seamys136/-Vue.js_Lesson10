<template>
  <div id="app">
      <div>
    <div class="title-logo">
      <img class="logo" alt="logo" src="../src/assets/LogoO.png">Interno
      <CompHeader/>
      <BannerOnePage/>
      <ProductDetails/>
      <CompFooter :imageUrl="require('../src/assets/LogoO.png')" logoName ="Interno"/>
    </div>
  </div>
  </div>
</template>

<script>

import BannerOnePage from './components/BannerOnePage.vue';
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

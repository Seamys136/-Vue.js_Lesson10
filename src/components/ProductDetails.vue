<template>
    <div class="product-details">
      <h1>{{ product.name }}</h1>
      <p>{{ formattedPrice }}</p>
      <p v-if="product.available">Available</p>
      <p v-else>Out of stock</p>
    </div>
  </template>
  
  <script>
  export default {
    name: "ProductDetails",
    data() {
      return {
        product: {
          name: "Sample Product",
          price: 99.99,
          available: true,
        },
      };
    },
    computed: {
      formattedPrice() {
        return `$${this.product.price.toFixed(2)}`;
      },
    },
  };
  </script>
  
  <style scoped>
  .product-details {
    padding: 20px;
    border: 1px solid #ccc;
    max-width: 300px;
    margin: 20px auto;
    text-align: center;
  }
  
  .product-details h1 {
    font-size: 1.5em;
    margin-bottom: 10px;
  }
  
  .product-details p {
    font-size: 1.2em;
    margin: 5px 0;
  }
  </style>
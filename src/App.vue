<template>
  <div id="app">
    <page-head />
    <div id="product-crousel">
      crousel
    </div>
    <div id="product-grid">
      <product />
      <product />
      <product />
      <product />
      <product />
      <product />
      <product />
    </div>
    <div id="footer-section">
      Footer section
    </div>
  </div>
</template>

<script>
import page_head from './components/page-head.vue'
import product from './components/products/product.vue'

export default {
  name: 'App',
  components: {
    'page-head': page_head,
    product

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

#product-crousel {
  height: 300px;
  width: 60%;
  border: 1px solid black;
  display: flex;
  justify-content: center;
}

#product-grid {
  height: 600px;
  width: 60%;
  border: 1px solid black;
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  gap: 10px
}

#footer-section {
  height: 200px;
  width: 100%;
  border: 1px solid black;
}
</style>

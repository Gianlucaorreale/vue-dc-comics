<template>
 <div  class="product-card">
    <img  :src="product.thumb" :alt= "product.series">
    <h3> {{product.series}} </h3>
 </div>
</template>

<script>
 export default {
 name: 'ProductCard',
 props: {
    product: Object
 }
}
</script>

<style scoped>
.product-card{
  margin: 0 10px;
  width: calc(100%/6 - 20px);
}
</style>
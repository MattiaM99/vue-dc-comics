<template>
  <div class="product-card">
    <div class="card">
      <img :src="product.thumb" :alt="product.series">
    </div>
      <h4>{{product.series}}</h4>
  </div>
</template>

<script>
export default {
  name: 'DcProduct',
  props:{
    product: Object,
  }
}
</script>


<style lang="scss">


.product-card{
  display: flex;
  flex-wrap: wrap;
  width: calc(100% / 6);
  .card{
    display: inline-block;
    border: none;
  }
  img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
    
  }
  h4{
    color: white;
    text-transform: uppercase;
    margin: 10px 8px 30px 8px ;
    font-size: 15px;
  }
}

</style>


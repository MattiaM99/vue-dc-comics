<template>
  <div class="main-container">
    <div class="container banner-top">
      <span>CURRENT SERIES</span>
    </div>
    <div class="container card-list">
       <DcProduct v-for="(product, index) in cardList" :key="index" :product="product" />
    </div>
    <div class="container banner-bottom">
      <span>LOAD MORE</span> 
    </div>
  </div>
</template>

<script>
import DcProduct from "./DcProduct.vue";
import cardList from "../assets/data/cardList.js"
export default {
  name: "Main",
  components:{
    DcProduct
  },
  data(){
   return{
     cardList
   }
  },
}
</script>

<style scoped lang="scss">
@import "../assets/style/vars.scss";
  .main-container{
    background-color: $main-bgc;
    padding-bottom: 50px;

    .banner-top{
    position: relative;

    span{    
      background-color: $primary-color;
      color: white;
      font-weight: bold;
      font-size: 20px;
      display: flex;
      text-align: center;
      justify-content: center;
      align-items: center;
      position: absolute;
      top: -25px;
      left: 0px;  
      width: 200px;
      padding: 8px;
      &:hover{
        cursor: pointer;
      }
    }
  }
}
  
  .card-list{ 
    padding: 50px 0;
    display: flex;
    flex-wrap: wrap;
     &:hover{
      cursor: pointer;
    }
  }
  .banner-bottom{
    display: flex;
    text-align: center;
    justify-content: center;
    align-items: center;
    width: 200px;
    height: 50px;
    background-color: $primary-color;
    color: white;
    font-weight: bold;
    &:hover{
      cursor: pointer;
    }
  }
</style>
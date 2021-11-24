<template>
  <div class="merch-container d-flex justify-content-center align-items-center">
    <div class="container merch-content ">
      <ul>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <a href="">DIGITAL COMICS</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
          <a href="">DIGITAL COMICS</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <a href="">DIGITAL COMICS</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
          <a href="">DIGITAL COMICS</a>
        </li>
        <li>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
          <a href="">DIGITAL COMICS</a>
        </li>
      </ul>  
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import "../assets/style/vars.scss";
  .merch-container{
    height: 200px;
    background-color: $primary-color;
    color: white;
  }
  li{
    display: inline;
    list-style: none;
    margin: 0 29px;
    img{
      width: 70px;
    }
    a{
      text-decoration: none;
      color: white;
      margin-left: 5px;
    }
  }
</style>
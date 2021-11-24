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
          <a href="">DC MERCHANDISE</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <a href="">SUBSCRIPTION</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
          <a href="">COMIC SHOP LOCATOR</a>
        </li>
        <li>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
          <a href="">DC POWER VISA</a>
        </li>
      </ul>  
    </div>
  </div>
</template>

<script>
export default {
  name: "Merch"
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
    margin: 0 20px;
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
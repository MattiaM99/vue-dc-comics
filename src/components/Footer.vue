<template>
  <footer>
    <div class="footer-top">
      <div class="container d-flex justify-content-between">
        <div class="footer-top-left d-flex justify-content-left align-items-center">
          <div class="row">
            <div class="col">
              <h3>DC COMICS</h3>
            <ul>
              <li><a href="">Characters</a></li>
              <li><a href="">Comics</a></li>
              <li><a href="">Movies</a></li>
              <li><a href="">TV</a></li>
              <li><a href="">Games</a></li>
              <li><a href="">Videos</a></li>
              <li><a href="">News</a></li>
            </ul>
            </div>
            <div class="col">
              <h3>SHOP</h3>
            <ul>
              <li><a href="">Shop DC</a></li>
              <li><a href="">Shop DC Collectibles</a></li>
            </ul>
            </div>
            <div class="col">
              <h3>DC</h3>
            <ul>
              <li><a href="">Terms Of Use</a></li>
              <li><a href="">Privacy Policy</a></li>
              <li><a href="">Ad choices</a></li>
              <li><a href="">adv</a></li>
              <li><a href="">jobs</a></li>
              <li><a href="">subs</a></li>
              <li><a href="">talent</a></li>
              <li><a href="">CPSC</a></li>
              <li><a href="">ratings</a></li>
              <li><a href="">shop help</a></li>
              <li><a href="">contact us</a></li>
            </ul>
            </div>
            <div class="col">
              <h3>SITES</h3>
            <ul>
              <li><a href="">dc</a></li>
              <li><a href="">MAD</a></li>
              <li><a href="">DC kids</a></li>
              <li><a href="">DC univ</a></li>
              <li><a href="">DC power visa</a></li>
            </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="logo-jumbo">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
    </div>
    <div class="footer-bottom">

    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped lang="scss">
@import "../assets/style/vars.scss";
  footer{
    height: 600px;
  }
  .footer-top{
    position: relative;
    height: 450px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    .footer-top-left{
      height: 560px;
    }
    .logo-jumbo{
      position: absolute;
      right: 100px;
      top: -60px;
      z-index: 1;
    }
  }
  .footer-bottom{
    position: relative;
    z-index: 100;
    height: 150px;
    background-color:#303030;
  }
  h3{
    color: white;
    font-size: 25px;
    font-weight: bold;
  }
  li{
    list-style: none;
    a{
      text-decoration: none;
      color: grey;
    }
  }
</style>
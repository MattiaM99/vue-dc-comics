<template>
  <nav class="navbar navbar-expand-lg bg-white static-top header">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="..\assets\img\dc-logo.png" alt="">
      </a>
      <div class="navbar-collapse collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">CHARACTERS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="#">COMICS</a>
          </li>   
          <li class="nav-item">
            <a class="nav-link" href="#">MOVIES</a>
          </li>   
          <li class="nav-item">
            <a class="nav-link" href="#">TV</a>
          </li>   
          <li class="nav-item">
            <a class="nav-link" href="#">GAMES</a>
          </li>   
          <li class="nav-item">
            <a class="nav-link" href="#">COLLECTIBLES</a>
          </li>   
          <li class="nav-item">
            <a class="nav-link" href="#">VIDEOS</a>
          </li>   
          <li class="nav-item">
            <a class="nav-link" href="#">FANS</a>
          </li>   
          <li class="nav-item">
            <a class="nav-link" href="#">NEWS</a>
          </li>   
          <li class="nav-item">
            <a class="nav-link" href="#">SHOP</a>
          </li>   
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
 name: "Header"
}
</script>

<style scoped lang="scss">

@import "../assets/style/vars.scss";

  .header{
    height: 200px;
  }

  a{
    color: $nav-font-col
  }

  .nav-link{
    color: $nav-font-col !important;
    font-weight: bold;
    padding: 0 15px !important;
  }

  .nav-link:hover{
    color: $link-color !important;
  }

  .active{
    color: $link-color !important;
    border-bottom: 3px solid $link-color;
  }

</style>
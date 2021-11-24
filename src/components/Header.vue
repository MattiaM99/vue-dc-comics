<template>
  <nav class="navbar navbar-expand-lg bg-white static-top header">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="..\assets\img\dc-logo.png" alt="">
      </a>
      <div class="navbar-collapse collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto">
          <li v-for="(link, index) in links" 
          :key="`ciclo-nav${index}`"
          :class="{active : (index === counter)}" class="nav-item">
            <a class="nav-link" href="#">{{link.name}}</a>
          </li>  
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
 name: "Header",

  data(){
    return{
      links:[
        {
          url: "/characters",
          name: "characters",
          active: false,
        },
        {
          url: "/comic",
          name: "comic",
          active: false,
        },
        {
          url: "/movies",
          name: "movies",
          active: false,
        },
        {
          url: "/tv",
          name: "tv",
          active: false,
        },
        {
          url: "/games",
          name: "games",
          active: false,
        },
        {
          url: "/collectibles",
          name: "collectibles",
          active: false,
        },
        {
          url: "/videos",
          name: "videos",
          active: false,
        },
        {
          url: "/fans",
          name: "fans",
          active: false,
        },
        {
          url: "/news",
          name: "news",
          active: false,
        },
        {
          url: "/shop",
          name: "shop",
          active: false,
        },
      ],
      counter: 1,
    }
  }
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
  &:hover{
    color: $primary-color !important;
  }
  }

  .active{
    color: $primary-color !important;
    border-bottom: 3px solid $primary-color;
  }

</style>
<template>
  <div class="d-flex justify-content-start align-items-center main-container">
    <div class="container">
      <h2>CONTENT HERE</h2>
    </div>
  </div>
</template>

<script>
export default {
  name:"Main"
}
</script>

<style scoped lang="scss">
@import "../assets/style/vars.scss";
  .main-container{
    height: 150px;
    background-color: $main-bgc;
  }
  h2{
    color: white;
  }
</style>
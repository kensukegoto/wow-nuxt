<template>
  <div class="container wow fadeInUp">
    <div class="block block--a"></div>
    <div class="block block--b"></div>
    <div class="block block--c"></div>
  </div>
</template>

<script>
export default {
  mounted(){
    new WOW().init();
  }
}
</script>

<style>
.wow {
  visibility: hidden;
}
.block{
  height: 500px;

}
.block--a{
  background-color: yellow;
}
.block--b{
  background-color: purple;
}
.block--c{
  background-color: pink;
}
</style>
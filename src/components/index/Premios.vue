<template>
  <div class="bg d-flex flex-column">
      <h1>PREMIOS INCRIVEIS</h1>
      <img class="align-self-center img-fluid" src="@/assets/trophies.png" alt="">
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.bg {
  background-color: #0d0030;
  color: white;
  background-image: url("~@/assets/bg.png");
  background-size: contain;
  background-position: bottom;
  background-repeat: no-repeat;
}
h1{
    font-size: 3em;
}
img{
    align-self: center;
    margin-top: 10em;
}
</style>
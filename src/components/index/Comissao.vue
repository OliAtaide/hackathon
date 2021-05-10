<template>
  <div class="bg">
    <h1>COMISSÃO ORGANIZADORA</h1>
    <div class="grid row">
      <div class="col">
        <img src="@/assets/aldiney.png" alt="" />
        <h6 class="text-center mt-3">Aldiney Doreto</h6>
      </div>
      <div class="col">
        <img src="@/assets/janaina.png" alt="" />
        <h6 class="text-center mt-3">Janaina Rodrigues</h6>
      </div>
      <div class="col">
        <img src="@/assets/joaopaulo.png" alt="" />
        <h6 class="text-center mt-3">João Paulo Q. dos Santos</h6>
      </div>
      <div class="col">
        <img src="@/assets/fernando.png" alt="" />
        <h6 class="text-center mt-3">Fernando L. de Oliveira Farias</h6>
      </div>
      <div class="col">
        <img src="@/assets/melise.png" alt="" />
        <h6 class="text-center mt-3">Melise C. Duarte de Almeida</h6>
      </div>
      <div class="col">
        <img src="@/assets/mauricio.png" alt="" />
        <h6 class="text-center mt-3">Mauricio Capra</h6>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@media only screen and (max-width: 600px) {
  h1{
    font-size: 2em !important;
  }
}
.bg {
  background-color: #f5f5f5;
}
h1 {
  font-size: 3em;
}
.grid {
  margin-top: 3em;
}
img {
  width: 90%;
}
h6{
  color: #1F0A57;
}
</style>
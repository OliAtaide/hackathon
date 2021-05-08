<template>
  <div class="bg d-flex align-items-center flex-column">
    <div class="title text-center">
      <h1>HACKATHON</h1>
      <h3>CAUSA BÁSICA DO ÓBITO</h3>
      <p>Codificar é preciso!</p>
    </div>
    <img src="@/assets/arrow-down.svg" alt="">
    <div class="box align-self-center d-flex flex-column">
      <h2>CODIFICAR É PRECISO!</h2>
      <p class="text-break">
        O objetivo do nosso Hackathon Causa Básica do Óbito é construir soluções
        inovadoras que auxiliem no registro das causas básicas de óbitos no
        Brasil, que compõem o Sistema Seletor de Causa Básica de Óbito.
      </p>
      <button class="button align-self-center">QUERO PARTICIPAR</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@media only screen and (max-width: 600px) {
  .box {
    width: 100% !important;
    padding: 2.5em !important;
  }
  .title p, .title h3{
    font-size: 1em !important;
  }
  .box p{
    font-size: 16px;
  }
  .box button{
    font-size: 1em !important;
  }
}
.bg {
  background-color: #0d0030;
  width: 100%;
  height: 100%;
  background-image: url("~@/assets/index-bg.png");
  background-size: contain;
  background-repeat: no-repeat;
}
.title h1{
  font-size: 5em;
  color: white;
}
.title h3{
  color: rgb(60, 154, 228);
  font-weight: 400;
}
.title p{
  font-style: italic;
  color: white;
}
img{
  margin: 5em;
}
.box {
  background-color: white;
  padding: 5em;
  margin: 5em;
}
.box h2{
  color: #1f0057;
}
p {
  font-family: Arial, Helvetica, sans-serif;
  padding: 1em 0 1em 0;
  font-size: 1.5em;
}
.button{
  padding: 1em;
  background-color: #ff7513;
  outline: none;
  border: none;
  color: white;
  font-size: 1.5em;
}
</style>
<template>
  <navbar/>
  <index/>
  <objetivos/>
  <fases/>
  <premios/>
  <apoio/>
  <comissao/>
  <participe/>
  <rodape/>
</template>

<script>
import Navbar from './components/parciais/Navbar.vue'
import Index from './components/index/Index.vue'
import Objetivos from './components/index/Objetivos.vue'
import Fases from './components/index/Fases.vue'
import Premios from './components/index/Premios.vue'
import Apoio from './components/index/Apoio.vue'
import Comissao from './components/index/Comissao.vue'
import Participe from './components/index/Participe.vue'
import Footer from './components/index/Footer.vue'

export default {
  name: 'App',
  components: {
    navbar : Navbar,
    index : Index,
    objetivos : Objetivos,
    fases: Fases,
    premios: Premios,
    apoio : Apoio,
    comissao : Comissao,
    participe : Participe,
    rodape : Footer,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lexend+Exa&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&display=swap');

* {
  padding: 0;
  margin: 0;
  font-family: 'Lexend Exa', sans-serif;
}

.bg{
  padding: 10em;
  overflow-x: hidden;
}
@media only screen and (max-width: 600px) {
  .bg {
    padding: 5em;
  }
  h1{
    font-size: 3em !important;
  }
}
</style>

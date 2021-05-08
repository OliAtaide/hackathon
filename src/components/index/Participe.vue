<template>
  <div class="bg row">
    <div class="col">
      <h1>PARTICIPE!</h1>
      <h4>Fique ligado(a) nas regras</h4>
      <h6>Inscrições de 02/11/2020 a 09/11/2020</h6>
      <p>
        Para se inscrever, é preciso preencher o formulário de inscrição, onde
        poderão participar equipes de 4 (quatro) membros, devendo ser
        organizadas preferencialmente da seguinte forma: - 1x Perfil Business,
        2x Hackers (Desenvolvedores) e 1x UX/UI (Design).
        <br/><br/>
        <small>
            <strong>Obs:</strong> Os membros da equipe deverão estar com matrícula ativa em
          instituição pública ou privada de ensino, em nível de curso técnico ou
          graduação. 
          <br/><br/>
          <strong>Canal para dúvidas:</strong> hackathon@navi.ifrn.edu.br
        </small>
      </p>
      <a href=""><i class="fab fa-instagram"></i></a>
      <a href=""><i class="fab fa-facebook-f"></i></a>
    </div>
    <div class="col">
        <img src="@/assets/rocket.png" alt="">
      <button class="button">QUERO PARTICIPAR</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h1{
    margin-bottom: 1em;
}
h6{
    margin: 1.5em 0 1.5em 0;
    color: #3C9AE4;
    font-weight: bold;
}
.button{
  padding: 1em;
  background-color: #ff7513;
  outline: none;
  border: none;
  color: white;
  font-size: 1.5em;
}
p, small, strong{
  font-family: Roboto, Arial, Helvetica, sans-serif;;
  font-size: 15px;
  color: #000000bf;
}
</style>
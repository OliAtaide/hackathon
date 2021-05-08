<template>
  <div class="bg">
    <h1>FASES DO EVENTO</h1>
    <div class="fases">
      <div class="fase">
        <h4>PERÍODO DE INSCRIÇÕES</h4>
        <h6>02/11/2020 a 09/11/2020</h6>
        <p>
          Para se inscrever, é preciso preencher o formulário de inscrição, onde
          poderão participar equipes de 4 (quatro) membros, devendo ser
          organizadas preferencialmente da seguinte forma: 1x Perfil Business,
          2x Hackers (Desenvolvedores) e 1x UX/UI (Design).
          <br /><br />
          <small>
            <strong>Obs:</strong> Os membros da equipe deverão estar com
            matrícula ativa em instituição pública ou privada de ensino, em
            nível de curso técnico ou graduação. <br /><br />
            <strong>Canal para dúvidas:</strong> hackathon@navi.ifrn.edu.br
          </small>
        </p>
        <a href="">
          <i class="fas fa-external-link-alt"></i>
          INSCREVA-SE AQUI!
        </a>
      </div>
      <div class="fase">
        <h4>LIVE DE ABERTURA</h4>
        <h6>14/11/2020 às 20h</h6>
        <p>
          Live que dará início ao evento. Já marque em sua agenda para não
          esquecer!
        </p>
      </div>
      <div class="fase">
        <h4>ETAPA 1: BRAINSTORMING E IDEAÇÃO</h4>
        <h6>14/11/2020 a 19/11/2020</h6>
        <p>
          A equipe participante deverá enviar um link de vídeo (ex: youtube) por
          meio do link abaixo. O vídeo deve ser em formato de pitch com duração
          de até 3min descrevendo a proposta de solução.
        </p>
        <a href="">
          <i class="fas fa-external-link-alt"></i>
          ENVIAR PROPOSTA
        </a>
      </div>
      <div class="fase">
        <h4>RESULTADO DA ETAPA 1: BRAINSTORMING E IDEAÇÃO</h4>
        <h6>14/11/2020 a 19/11/2020</h6>
        <a href="">
          <i class="fas fa-external-link-alt"></i>
          RESULTADO ETAPA 1
        </a>
      </div>
      <div class="fase">
        <h4>ETAPA 2: PROTOTIPAÇÃO E SOLUÇÃO</h4>
        <h6>21/11/2020 a 26/11/2020</h6>
        <p>
          A equipe participante deverá produzir um protótipo de média fidelidade
          e enviar um link de vídeo (ex: youtube) por meio do link abaixo. O
          vídeo deve ter duração de até 2min explicando o protótipo
          desenvolvido.
        </p>
        <a href="">
          <i class="fas fa-external-link-alt"></i>
          ENVIAR PROPOSTA
        </a>
      </div>
      <div class="fase">
        <h4>RESULTADO DA ETAPA 2: PROTOTIPAÇÃO E SOLUÇÃO</h4>
        <h6>14/11/2020 a 19/11/2020</h6>
        <a href="">
          <i class="fas fa-external-link-alt"></i>
          RESULTADO ETAPA 1
        </a>
      </div>
      <div class="fase">
        <h4>ETAPA FINAL: APRESENTAÇÃO DO MVP E PREMIAÇÃOX</h4>
        <h6>30/11/2020</h6>
        <p>
          A equipe participante deverá enviar um link de vídeo (ex: youtube) por
          meio do link abaixo. O vídeo deve ser em formato de pitch e ter
          duração de até 2min explicando o MVP (Produto Mínimo Viável). Além
          disso, deve também disponibilizar os arquivos da solução proposta
          através de pastas na nuvem (ex: github, google drive...).
        </p>
        <a href="">
          <i class="fas fa-external-link-alt"></i>
          ENVIAR PROJETO
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.bg{
  background-image: url("~@/assets/network.png");
  background-size: contain;
  background-position: center;
  background-repeat: no-repeat;
}
.fases {
  margin-top: 8em;
  width: 70%;
}
.fase {
  margin: 5em;
}
h6,
a {
  color: #3c9ae4;
  font-weight: bold;
}
a,
p,
small,
strong {
  font-family: Roboto, Arial, Helvetica, sans-serif !important;
}
p {
  margin-top: 2em;
}
</style>
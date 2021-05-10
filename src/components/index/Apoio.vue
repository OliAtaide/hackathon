<template>
  <div class="bg">
    <h1>INFORMAÇÕES DE APOIO</h1>
    <div class="row">
      <div class="col1 col-sm-6">
        <div>
          <h4>Introdução à Causa Básica do Óbito</h4>
          <p>
            Todos os dias milhares de mortes são registradas no Brasil. Para
            simplificar o registro desses óbitos, foi criado o sistema de
            Codificação das Causas Básicas do Óbito. Ele serve para que seja
            possível identificar a causa primária da morte de uma pessoa, como
            por exemplo uma doença ou uma arma.
            <br />
            <br />
            Dessa forma, a utilização da codificação do óbito se amplia
            exponencialmente e é identificada como uma demanda permanente do
            sistema de saúde. Sendo natural que a codificação do óbito passe a
            ser uma tarefa institucional primordial a ser assumida organicamente
            pelo Sistema Único de Saúde.
          </p>
        </div>
        <div>
          <h4>Objetivo</h4>
          <p>
            Construir soluções inovadoras que auxiliem na codificação da causa
            básica do óbito que compõem o Sistema Seletor de Causa Básica de
            Óbito
          </p>
        </div>
        <div>
          <h4>Regulamento do evento</h4>
          <a href="">
            <i class="fas fa-external-link-alt"></i>
            CONFERIR REGULAMENTO COMPLETO
          </a>
        </div>
      </div>
      <div class="col2 col-sm-5">
        <h4>Eixos Temáticos</h4>
        <ul>
          <li>
            <h6>
              1 - Tecnologias para melhoramento na codificação da causa básica
              do óbito:
            </h6>
            <p>
              Propor soluções inovadoras que auxiliem a codificação da causa do
              óbito, incluindo validação da codificação especificada e propor a
              codificação mais acurada da CBO se necessário.
            </p>
          </li>
          <li>
            <h6>2 - Desenvolvimento de Sistemas de Recomendação em CBO:</h6>
            <p>
              Propor sistemas de recomendação baseados em histórico de
              codificação da causa do óbito, que atuem como assistentes virtuais
              dos profissionais em CBO, a partir de modelos preditivos
              especializados na Classificação Internacional de Doenças e
              Problemas Relacionados à Saúde (CID-10).
            </p>
          </li>
          <li>
            <h6>3 - Tecnologias para Treinamento de Profissionais em CBO:</h6>
            <p>
              Propor recursos educacionais abertos que auxiliem no processo de
              formação dos profissionais em CBO, incluindo simuladores da
              codificação de DO Declaração de óbito , jogos sérios ou objetivos
              de aprendizagem como foco em codificação da causa básica do óbito
            </p>
          </li>
        </ul>
        <p class="obs fst-italic">
          A declaração de óbito é composta por campos informativos como Idade,
          Sexo, setor laboral, e pricipalmente doenças ou agravos que levaram a
          pessoa ao óbito. Este último é chamado Bloco V, é dele que o
          codificador retira as informações necessária para codificar a causa
          básica do óbito.
          <br />
          Aqui pretende-se buscar tecnologia que simula esse processo de
          codificação e auxilie a memorização das regras .
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@media only screen and (max-width: 600px) {
  .col2{
    margin-left: 0 !important;
  }
  h1{
    font-size: 2em !important;
  }
}
.bg {
  background-color: white;
}
.row {
  margin-top: 4em;
}
h4 {
  font-weight: bold;
  color: #3c9ae4;
  font-size: 1.4em;
  margin: 1em 0 1em 0;
}
.col2 {
  margin-left: 5em;
}
h6,
p,
a {
  font-size: 15px;
  font-family: Roboto, Arial, Helvetica, sans-serif;
}
h6 {
  font-weight: bold;
}
ul {
  list-style-type: none;
  padding-left: 0;
}
ul li {
  margin-bottom: 2em;
}
.obs {
  font-size: 12px;
}
a {
  color: #ff7513;
  font-weight: bold;
}
</style>
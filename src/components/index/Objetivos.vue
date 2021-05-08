<template>
  <div class="bg">
    <h1>OBJETIVOS</h1>
    <div class="row row-cols-sm-3">
      <div class="col-sm">
        <img src="@/assets/rocket.svg" alt="" />
        <h4>Fomento à inovação</h4>
        <p>
          Desenvolver uma <strong>cultura de inovação e criação</strong> de novas ideias para
          solucionar problemas presentes em nossa sociedade
        </p>
      </div>
      <div class="col-sm">
        <img src="@/assets/homework.svg" alt="" />
        <h4>Fonte de aprendizado</h4>
        <p>
          Oportunidade de aprendizado para todos os participantes, pois cada
          atividade <strong>estimula a criatividade e se transforma em conhecimento</strong>
        </p>
      </div>
      <div class="col-sm">
        <img src="@/assets/knowledge.svg" alt="" />
        <h4>Aceleração de ideias</h4>
        <p>
          <strong>Surgimento de ideias incríveis</strong> que poderão se tornarem projetos de
          grande impacto na vida de muitas pessoas direta ou indiretamente.
        </p>
      </div>
      <div class="col-sm">
        <img src="@/assets/team.svg" alt="" />
        <h4>Trabalho em equipe</h4>
        <p>
          <strong>Interação entre participantes</strong> de multidisciplinas, que poderão
          trabalhar juntos e aprenderem coisas novas
        </p>
      </div>
      <div class="col-sm">
        <img src="@/assets/box.svg" alt="" />
        <h4>Desafio</h4>
        <p>
          Promover desafios como esse, faz com que jovens e adultos se desafiem
          e possam até mesmo dar o próximo passo em suas carreiras
        </p>
      </div>
      <div class="col-sm">
        <img src="@/assets/window.svg" alt="" />
        <h4>Implementação de projetos</h4>
        <p>
          Incentivar a implementação de projetos que estão guardados ou que
          precisam ser melhorados
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.bg {
  background-color: #1f0057;
  color: white;
}
p, strong {
  font-family: Roboto, Arial, Helvetica, sans-serif;
  color: #ffffffbf;
  font-size: 15px;
  width: 75%;
}
h1 {
  margin-bottom: 1em;
  font-size: 3.2em;
}
h4{
  margin: 1em 0 1em 0;
}
.col-sm{
  margin: 1em 0 2em 0;
}
</style>
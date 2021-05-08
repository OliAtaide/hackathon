<template>
  <nav class="navbar navbar-expand-lg navbar-dark shadow-lg">
    <div class="container-fluid">
      <a href="" class="navbar-brand">
        <img src="@/assets/navbar-logo.png" alt="">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
        <ul class="navbar-nav justify-content-between">
          <li class="nav-item">
            <a href="" class="nav-link">OBJETIVOS</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">O EVENTO</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">INSCRIÇÕES</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link">INFORMAÇÕES</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
@media only screen and (max-width: 600px) {
  .navbar{
    padding: 0 !important;
  }
}
.navbar {
  background-color: #0d0030;
  height: 5em;
  padding-left: 9em;
  padding-right: 9em;
}
#navbarSupportedContent{
  background-color: #0d0030;
}
</style>
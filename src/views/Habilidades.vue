<template>
  <div id="habilidades">
    <h2 style="text-align: center">Mis Habilidades</h2>
    <div class="habilidades-container">
      <div class="card">
        <img src="../assets/dw.png" alt="Desarrollo" />
        <div class="card-body">
          <h5 class="card-title text-center">Desarrollo Web</h5>
          <p class="card-text">
            Creacion de formularios,estilizar paginas,asignar funcionadalidades del lado del frontend
          </p>
        </div>
      </div>
      <div class="card">
        <img src="../assets/ci.png" alt="Codeigniter" />
        <div class="card-body">
          <h5 class="card-title text-center">Codeigniter</h5>
          <p class="card-text">
            Construcción de paginas web mediante el framework de PHP
            basado en el modelo MVC
          </p>
        </div>
      </div>
      <div class="card">
        <img src="../assets/psql.png" alt="Postgres" />
        <div class="card-body">
          <h5 class="card-title text-center">Postgres</h5>
          <p class="card-text">
            Poseo experiencia en este motor de base de datos,consultas completas,creacion de bases de datos
            , etc.
          </p>
        </div>
      </div>
      <!-- <div class="card">
        <img src="../assets/logo.png" alt="Postgres" />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div> -->
    </div>
  </div>
</template>

<style scoped>
.habilidades-container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}

.card {
  margin: 20px;
  width: 30%;
  -webkit-box-shadow: 3px 5px 24px 4px rgba(190, 190, 190, 0.57);
  box-shadow: 3px 5px 24px 4px rgba(190, 190, 190, 0.57);
  display: flex;
  justify-content: center;
}

.card img {
  max-width: 60%;
  display: block;
  margin: auto;
}
p{
  text-align: center;
}
</style>
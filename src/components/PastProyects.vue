<template>
  <div class="proyects">
    <h2 class="proyects__tittle text-center m-4 text-light">Proyectos que he realizado</h2>
    <div class="row d-flex justify-content-center">
      <div class="col-md-3">
        <div class="card m-2" style="height:400px">
          <img src="../assets/cards/Random User.png" class="card-img-top" alt="Imagen proyecto random user" height="200px">
          <div class="card-body">
            <h5 class="card-title">Usuario al azar con API</h5>
            <p class="card-text">Se cargan dos usuarios al azar de una API con una sala de chat.</p>
            <hr>
            <div>
              <a href="https://github.com/igykun/desafio-randomUser" class="btn btn-primary m-2" target="_blank">Ir al repositorio</a><a href="https://desafio-random-user.vercel.app/" class="btn btn-primary m-2" target="_blank">Ver</a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card m-2" style="height:400px">
          <img src="../assets/cards/Desafio Pokemon.png" class="card-img-top" alt="Imagen proyecto random user" height="200px">
          <div class="card-body">
            <h5 class="card-title">¿Quien es ese pokemon?</h5>
            <p class="card-text">Se cargan 20 cartas con imagenes borrosas de pokemon, si adivinas bien el nombre la imagen se aclara.</p>
            <hr>
            <div>
              <a href="https://github.com/igykun/Desafio-Pokemon" class="btn btn-primary m-2" target="_blank">Ir al repositorio</a><a href="https://desafio-pokemon-jade.vercel.app/" class="btn btn-primary m-2" target="_blank">Ver</a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card m-2" style="height:400px">
          <img src="../assets/cards/Desafio Firebase 1.png" class="card-img-top" alt="Imagen proyecto random user" height="200px">
          <div class="card-body">
            <h5 class="card-title">CRUD - Firebase</h5>
            <p class="card-text">Un CRUD basico utilizando firebase como base de datos.</p>
            <hr>
            <div>
              <a href="https://github.com/igykun/Desafio-firebase-1" class="btn btn-primary m-2" target="_blank">Ir al repositorio</a><a href="https://desafio-firebase-1.netlify.app/" class="btn btn-primary m-2" target="_blank">Ver</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'PastProyects',
  data(){
    return{

    }
  }
}
</script>
<style scoped>

</style>

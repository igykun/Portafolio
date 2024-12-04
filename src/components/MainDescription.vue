<template>
  <div class="description w-100 text-light">
    <div class="row">
      <div class="col-md-5 m-4 text-center">
        <img class="description__img" src="../assets/Foto.jpg" alt="Mi Foto" height="250px" width="180px">
      </div>
      <div class="col-md-6 d-flex justify-content-center flex-column">
        <h2 class="description__title text-center">
          {{ name }}
        </h2>
        <p class="description__text text-center">
          {{ description }}
        </p>
      </div>
    </div>
    <hr>
  </div>
</template>
<script>
export default {
  name: 'MainDescription',
  data(){
    return{
      name: 'Ignacio Jara Pérez',
      description: 'Programador front-End con experiencia en Javascript y VueJs. Estudie en INACAP analista programador, por lo que cuento con cierto nivel de conocimiento en Back-End y base de datos. Ademas acabo de completar un curso de Front-End en DESAFIO LATAM.'
    }
  }
}
</script>
<style scoped>
  .description{
    background-color: #8338ec;
  }
  .description__img{
    border-radius: 100px;
  }
</style>

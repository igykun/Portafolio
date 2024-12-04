<template>
  <div class="experience container">
    <h2 class="text-center">
      Experiencia laboral
    </h2>
    <div class="row">
      <!-- <div class="col-md-6 mb-4" v-for="(job, index) in jobs" :key="index">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">
              {{job.company}}
            </h5>
            <h6 class="card-subtitle mb-2 text muted">
              {{job.period}} - {{job.position}}
            </h6>
            <p class="card-text">
              {{job.description}}
            </p>
          </div>
        </div>
      </div> -->
      <p class="text-center m-2"><strong>Aun no tengo Experiencia laboral pero aprendo rapido, soy siempre puntual y pretendo continuar aprendiendo para mejorar mis habilidades constantemente</strong></p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'WorkExperience',
  data(){
    return{
      jobs: [
        {
          company: '.',
          position: '.',
          period: '.',
          description: '.'
        },
      ]
    }
  }
}
</script>
<style>
  .card{
    border: none;
    box-shadow: 0 4px 8px 0 black ;
  }
</style>

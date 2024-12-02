<!-- eslint-disable no-unused-vars -->

<script>
import Education from '@/components/Education.vue';
import WorkExperience from '@/components/WorkExperience.vue';
export default{
  name: 'AboutView',
  components:{
    Education,
    WorkExperience,
  },
  data(){
    return{

    }
  }
}
</script>

<template>
  <div class="about">
    <h1 class="text-center">¿Que experiencia tengo?</h1>
    <Education />
    <WorkExperience />
    <hr>
    <p class="text-center"><strong>Aun no tengo Experiencia laboral pero aprendo rapido, soy siempre puntual y pretendo continuar aprendiendo para mejorar mis habilidades constantemente</strong></p>
  </div>
</template>
<style>
</style>

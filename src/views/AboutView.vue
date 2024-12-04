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
  </div>
</template>
<style scoped>
  .about{
    background-color: #353535;
    color: #f2f3f4;
    height: 100%;
  }
  *{
    background-color: #353535;
  }
</style>

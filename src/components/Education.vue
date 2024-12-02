<template>
  <div class="education container">
    <h2 class="text-center">
      Educación
    </h2>
    <ul class="list-group border-0">
      <li class="list-group-item" v-for="(edu, index) in education" :key="index">
        <h5 class="">
          {{edu.instituto}}
        </h5>
        <p>{{edu.carrera}} {{edu.periodo}}</p>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Education',
  data(){
    return{
      education: [
        {
          instituto: 'INACAP',
          carrera: 'Analista programador',
          periodo: '2019 - 2021'
        },
      ]
    }
  }
}
</script>
<style>
  
</style>
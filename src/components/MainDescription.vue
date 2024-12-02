<template>
  <div class="description container">
    <h2 class="description__title text-center">
      {{ name }}
    </h2>
    <p class="description__text text-center">
      {{ description }}
    </p>
  </div>
</template>
<script>
export default {
  name: 'MainDescription',
  data(){
    return{
      name: 'Ignacio Jara',
      description: 'Programador front-End con experiencia en Javascript y VueJs'
    }
  }
}
</script>
<style>

</style>

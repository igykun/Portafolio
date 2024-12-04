<template>
    <section id="skills" class="skills container">
        <h2 class="skills__title text-center m-2">
            Mis habilidades
        </h2>
        <div class="skills__list row w-100 text-center">
            <div class="skills__item col-3">
                <i class="skills__i fa-brands fa-html5 text-orange"></i>
                <p class="skills__name">HTML</p>
            </div>
            <div class="skills__item col-3">
                <i class="skills__i fa-brands fa-git-alt text-darkorange"></i>
                <p class="skills__name">Git</p>
            </div>
            <div class="skills__item col-3">
                <i class="skills__i fa-brands fa-css3-alt text-lightblue"></i>
                <p class="skills__name">CSS</p>
            </div>
            <div class="skills__item col-3">
                <i class="skills__i fa-brands fa-github text-lightblack"></i>
                <p class="skills__name">Github</p>
            </div>
            <div class="skills__item col-3">
                <i class="skills__i fa-brands fa-github text-pink"></i>
                <p class="skills__name">Sass</p>
            </div>
            <div class="skills__item col-3">
                <i class="skills__i fa-brands fa-js text-yellow"></i>
                <p class="skills__name">JavaScript</p>
            </div>
            <div class="skills__item col-3">
                <i class="skills__i fa-brands fa-bootstrap text-purple"></i>
                <p class="skills__name">Bootstrap</p>
            </div>
            <div class="skills__item col-3">
                <i class="skills__i fa-brands fa-vuejs text-lightgreen"></i>
                <p class="skills__name">Vue</p>
            </div>
        </div>
    </section>
</template>
<script>
export default {
  name: 'MyAbilities',
  data(){
    return{

    }
  }
}
</script>
<style scoped>
  .skills{
    background-color: #cdb4db;
    border-radius: 30px;
  }
</style>

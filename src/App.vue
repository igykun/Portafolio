<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import Education from './components/Education.vue';
// import WorkExperience from './components/WorkExperience.vue';
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item m-2">
          <RouterLink to="/">Home</RouterLink>
        </li>
        <li class="nav-item m-2">
          <RouterLink to="/about">Sobre mí</RouterLink>
        </li>
        <li class="nav-item m-2">
          <RouterLink to="/contact">Contacto</RouterLink>
        </li>
      </ul>
    </div>
  </div>
</nav>
  <RouterView />
</template>

<style scoped>
</style>

<template>
  <div class="contact">
    <div class="contact__wrapper d-flex justify-content-center flex-column">
      <h2 class="contact__tittle text-center m-2">
        Contactame
      </h2>
      <form action="" class="contact__form text-center">
        <div class="name">
          <label for="contactName" class="contact__label m-2">Nombre :</label>
          <input type="text" id="contactName" placeholder="Ingresa tu nombre" class="contactName" />
        </div>
        <div class="email">
          <label for="contactEmail" class="contact__label m-2">Correo :</label>
          <input type="email" id="contactEmail" placeholder="Ingresa tu correo" class="contactEmail">
        </div>
        <div class="mensaje">
          <textarea name="contactMessage" id="contactMessage" maxlength="200" class="m-2"></textarea>
        </div>
        <div class="enviar">
          <button class="btn m-2 button__enviar text-light">
            Enviar
          </button>
        </div>
      </form>
    </div>
    <div class="contact__socials">
      <h2 class="contact__tittle text-center">
        Tambien puedes encontrarme en
      </h2>
      <div class="contact__icons d-flex flex-row text-center justify-content-around align-content-center">
        <!-- <div class="col-md-3 text-center"> -->
          <a href="https://www.instagram.com/igysaurus/" class="p-2" target="_blank"><i class="fa-brands fa-instagram"></i></a>
          <h6 class="my-auto">Instagram</h6>
        <!-- </div>
        <div class="col-md-3 text-center"> -->
          <a href="https://github.com/igykun" class="p-2" target="_blank"><i class="fa-brands fa-github"></i></a>
          <h6 class="my-auto">GitHub</h6>
        <!-- </div>
        <div class="col-md-3 text-center"> -->
          <a href="https://www.linkedin.com/in/ignacio-jara-p%C3%A9rez-b81321153/"  class="p-2" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
          <h6 class="my-auto">Linkedln</h6>
        <!-- </div>
        <div class="col-md-3 text-center"> -->
          <a href='mailto:ignaciojaraperez@gmail.com' class="p-2" target="_blank"><i class="fa-solid fa-envelope"></i></a>
          <h6 class="my-auto">Correo Electronico</h6>
        <!-- </div> -->
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'ContactMe',
  data(){
    return{
    }
  }
}
</script>
<style scoped>
  .contactName{
    width: 500px;
  }
  .contactEmail{
    width: 500px;
    margin-left: 10px;
  }
  #contactMessage{
    width: 600px;
    height: 100px;
  }
  i{
    font-size: 40px;
  }
  .contact__icons{
    display: flex;
    flex-direction: column;
  }
  .button__enviar{
    width: 150px;
  }
  .contact__wrapper{
    background-color: #E195AB;
    width: 50%;
    border-radius: 50px;
    margin: 10px auto;
  }
  .name, .mensaje{
    background-color: #FFCCE1;
  }
  .email, .enviar{
    background-color: #FFF5D7;
  }
  input, textarea{
    border-radius: 20px;
    border: 0px;
  }
  .button__enviar{
    background-color: #B03052 !important;
  }
</style>

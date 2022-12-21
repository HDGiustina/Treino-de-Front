
<template>
  <div class="container">
    <Formulario />
    <img src="https://st3.depositphotos.com/3218907/17568/v/600/depositphotos_175689166-stock-illustration-explosion-shrapnel-from-the-explosion.jpg" alt="Banner" class="banner">
  </div>
</template>

<script>
  import Formulario from "../components/Formulario-Login.vue"

  export default {
    name: "Login",
    components: {
      Formulario
    }
  }
</script>

<style scoped>
  
  .container{
    display: flex;
    padding: 0px;
  }
  .banner{
    width: 50%;
    display: flex;
  }
</style>
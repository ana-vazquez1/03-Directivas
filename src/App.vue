<template>
  <div>
    <h1>Universidad Tecnológica de Tehuacán</h1>
    <h2>APW</h2>
    <h3>Grupo 4B</h3>

    <h1>Directivas en VUE.js</h1>
    <hr>
    <h2>v.text</h2>
    <span v-text="'Hola desde la directiva v-text'"></span>
    <br>
    <span>Hola desde la directiva v-text</span>
    <br>
    <span v-text="titulo"></span>
    <br>
    Esta es una trasmutacion de texto {{ titulo }}, con una variable prop 
    <br>
    <span v-text="titulo"></span>
    <br><br>
  

  </div>
</template>

<script>
  export default{
    data:() =>({
      titulo: "Hola desde VUE.js",
    }),
  };
</script>
<style scoped>
  div{
    text-align: center;
    margin: 0px 2rem;

  }
</style>
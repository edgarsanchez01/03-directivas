<template>
  <div>
    <h1>Directivas en VUE.js</h1>
    <h2>Grupo 3B</h2>
    <hr />
    <h2>v.text</h2>
    <span v-text="'Hola desde la directiva v-text'"></span>
    <br>
    <span>Hola desde la directiva v-text</span>
    <br>
    <span v-text="titulo"></span>
    <br>
    esta es una trasmutacion de texto con una variable prop <br>
    {{titulo}}
  </div>
</template>
<script>
  export default {
    data: () => ({
      titulo: "Hola desde VUE.js",
    }),
  }
</script>

<style scoped>
  div{
    text-align: center;
    margin: 0px 2rem;
  }
</style>
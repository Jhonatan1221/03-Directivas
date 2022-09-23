<template>
  <div>
    <h1>Directivas en VUE.JS</h1>
    <hr>
    <h2>V.text</h2>
  <span v-text="'hola la directiva v-text'"></span>
  <br>
  <samp>hola desde la directiva <v-text></v-text></samp>
  <br>
  <span v-text="Titulo"></span>
  esta es una transmutacion de texto con una <br>
  {{titulo}}
  

  </div>
</template>

<script>
export default {
  data:() =>({
    titulo:"hola desde",
  }),
};
</script>
<style scoped>
div{
  text-align: center;
  margin: 0px 2rem;
}

</style>
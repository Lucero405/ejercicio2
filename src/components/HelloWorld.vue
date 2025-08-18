<template>
  <div>
    <h1>{{ msg }}</h1>
    <h3  class="mb-3 animate__animated animate__lightSpeedInLeft">Ejercicio Previo al Examen</h3>
    <h5 class="hello animate__animated animate__jackInTheBox">Lucero Morales Moreno</h5>
 <form>
        <div>
            <div class="cont">
             <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            </div>
            </div>
  <button type="button" @click="mostrarMensaje =!mostrarMensaje" class="btn btn-outline-warning ">Visualizar</button>
  <p v-if="mostrarMensaje">Este es una prueba previa al examen</p>
  </form>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return{
      mostrarMensaje: false,
    };
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.cont
{
  margin: auto;
  border: 3px solid;
  width: 30%;

}
</style>


<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <h2>Repositorios</h2>
    <ul>
      <li><a href="https://github.com/naranjocespedes/pro_autentificar_.git" target="_blank">Autentificar</a></li>
      <li><a href="https://github.com/naranjocespedes/imagen_base64.git" target="_blank">imagen_base64_</a></li>
      <li><a href="https://github.com/naranjocespedes/vue-base64_pro.git" target="_blank">vue_base64_</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: ':::BIENVENIDO, ESTA ES LA PRUEBA:::'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
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
</style>

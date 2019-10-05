<template>
  <div id="app">
    <h2>Projekt17B</h2>
    <h1>Nový začiatok</h1>
    <h3>Este jeden mali podnadpis pre commit</h3>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
#app {
  border: 2px solid #cecece;
  border-radius: 50px 50px 10px 10px;
  height: 80vh;
  width: 80%;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: #e4e4e4;
  margin: 50px auto;
}

h1, h2 {
  font-weight: 900;
}

h2 {
  color: red;
  font-weight: 900;
  text-decoration: underline;
  font-style: italic;
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

<template>
  <iframe src="http://localhost:8080/" frameborder="0"></iframe>
  <iframe src="http://localhost:8080/" frameborder="0"></iframe>
  <iframe src="http://localhost:8080/" frameborder="0"></iframe>
  <hr>

  <iframe src="http://localhost:8080/" frameborder="0"></iframe>
  <iframe src="http://localhost:8080/" frameborder="0"></iframe>
  <iframe src="http://localhost:8080/" frameborder="0"></iframe>

</template>

<script>

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

iframe{
  
  width: auto;
  height: 48vh;
  margin-right: 20px
}
</style>

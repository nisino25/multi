<template>
  <iframe src="http://localhost:8080/" frameborder="0"></iframe>
  <iframe src="http://localhost:8080/" frameborder="0"></iframe>
  <iframe src="http://localhost:8080/" frameborder="0"></iframe>
  <!-- <hr> -->
  <br>

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
  margin-top: 5px;
  
  width: auto;
  height: 49vh;
  margin-right: 20px;


  -ms-zoom: 0.9;
  -moz-transform: scale(0.9);
  -moz-transform-origin: 0 0;
  -o-transform: scale(0.8);
  -o-transform-origin: 0 0;
  -webkit-transform: scale(0.9);
  -webkit-transform-origin: 0 0;
  
}

#wrap { width: 600px; height: 390px; padding: 0; overflow: hidden; }
    #frame { width: 800px; height: 520px; border: 1px solid black; }
    #frame {
        
    }


</style>

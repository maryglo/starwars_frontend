<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col-4 mx-auto d-flex justify-content-center flex-wrap">
          <img width="320" alt="Starwars Logo" src="./assets/Star_Wars_Logo.png" class="mx-auto d-block">
        </div>
      </div>
      <Main/>
    </div>
  </div>
</template>

<script>
import Main from './components/Main.vue'

export default {
  name: 'app',
  components: {
    Main
  }
}
</script>

<style>
#app {
  font-family: 'Roboto', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

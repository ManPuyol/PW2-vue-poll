<template>
    <div id="app">
      <h1>¿Cuál es tu lenguaje de programación favorito?</h1>
      <Poll />
    </div>
  </template>
  
  <script>
  import Poll from './Poll.vue';
  
  export default {
    name: 'App',
    components: {
      Poll
    }
  }
  </script>
  
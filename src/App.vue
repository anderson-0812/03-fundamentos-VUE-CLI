<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- con los : estoy vinculando este start con el prop del componente para q interprete el tipo de dato  -->
  <!-- <Counter :start="15"></Counter>  -->
  <Counter :start="15"></Counter> 
  <!-- <Counter title="Entraron"></Counter> -->
  <!-- <Counter title=""></Counter> -->
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Counter from './components/Counter.vue'

export default {
  name: 'App',
  components: {
    Counter
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
  margin-top: 60px;
}
</style>

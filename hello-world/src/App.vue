<template>
  <div id="app">
    <HelloWorld/>
    <!-- <LoginForm />
    <LoginFormNext/>
    <CalculatorNew/> -->
    <!-- <ArrayNew/> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
// import LoginForm from './components/LoginForm.vue';
// import LoginFormNext from './components/LoginFormNext.vue';
// import CalculatorNew from './components/CalculatorNew.vue'
// import ArrayNew from './components/ArrayNew.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    // LoginForm,
    // LoginFormNext,
    // CalculatorNew,
    // ArrayNew
  },
  
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

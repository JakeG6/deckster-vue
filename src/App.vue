<template>
  <div id="app">
    <Home />
    <NewDeckForm />
  </div>
</template>

<script>
import Home from './components/Home.vue'
import NewDeckForm from './components/NewDeckForm.vue'

export default {
  name: 'app',
  components: {
    Home,
    NewDeckForm
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
</style>

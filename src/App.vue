<template>
  <div id="app">
  <Title />
  <Jumbodron />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Jumbodron from './components/Jumbodron.vue'

export default {
  name: 'App',
  components: {
    Title,
    Jumbodron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

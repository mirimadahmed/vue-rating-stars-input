<template>
  <div id="app">
    <rating-input />
  </div>
</template>

<script>
import RatingInput from './components/RatingInput.vue'

export default {
  name: 'app',
  components: {
    RatingInput
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

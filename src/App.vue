<template>
  <div id="app">
    <MyCalculator />
  </div>
</template>

<script>
import MyCalculator from "./components/MyCalculator.vue";

export default {
  name: 'app',
  components: {
    MyCalculator
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

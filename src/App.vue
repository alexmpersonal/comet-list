<template>
  <div id="app">
    <CometList/>
  </div>
</template>

<script>
import CometList from './components/CometList.vue'

export default {
  name: 'app',
  components: {
    CometList
  }
}
</script>

<style>
@import "https://cdn.materialdesignicons.com/2.5.94/css/materialdesignicons.min.css";
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

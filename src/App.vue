<template>
  <div id="app">
    <WorkTime msg="Welcome to Your Vue.js App"/>
  </div>
</template>
<script>
import WorkTime from './components/WorkTime.vue'
export default {
  name: 'App',
  components: {
    WorkTime
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
textarea { 
  -webkit-appearance: none;
}
input[type="text"] {
  -webkit-appearance: none;
}
</style>

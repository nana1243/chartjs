<template>
  <HelloWorld msg="Practice Chart.js"/>
  <ChartExample/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ChartExample from "@/components/ChartExample";

export default {
  name: 'App',
  components: {
    HelloWorld,
    ChartExample
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

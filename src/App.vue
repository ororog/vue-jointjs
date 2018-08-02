<template>
  <div id="app">
    <img src="./assets/logo.png">
    <JointJs/>
    <router-view/>
  </div>
</template>

<script>
import JointJs from '@/components/JointJs'

export default {
  name: 'App',
  components: {
    JointJs
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

<template>
  <div id="app">
    <img src="./assets/logo.png">
    <profile-card/>
  </div>
</template>

<script>
import ProfileCard from './components/ProfileCard'

export default {
  name: 'App',
  components: {
    ProfileCard
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

<template>
  <div id='app'>
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
@import url('https://fonts.googleapis.com/css?family=Lato');
#app {
  font-family: 'Lato', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

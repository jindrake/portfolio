<template>
  <div class="card">
    Hello World
  </div>
</template>

<script>
export default {
  name: 'profile-card',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.card {
  color: #42b983;
  background-color: black;
  height: 100%;
  width: 40%;
  position: absolute;
  top: 0px;
  left: 0px;
}
</style>

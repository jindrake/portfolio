<template>
  <div id='card'>
    <avatar/>
    <br>
    <div id='name'>
      JETHRO TANJAY <br>
      <div class='light'>Software Engineer</div>
    </div>
  </div>
</template>

<script>
import Avatar from './Avatar'
export default {
  name: 'profile-card',
  data () {
    return {
    }
  },
  components: {
    Avatar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#card {
  background-color: #32936f;
  width: 40%;
  position: absolute;
  height: 100%;
  left: 0px;
  top: 0px;
  text-align: center;
  font-size: 30px;
}
.light {
  color: rgb(221, 221, 221);
  font-size: 20px;
}
#name {
  color: white;
}
@media only screen and (max-width: 768px) {
  #card {
    height: 200px;
    width: 100%;
    font-size: 20px;
  }
  #name {
    margin-top: -100px;
    color: white;
  }
  .light {
    font-size: 13px;
  }
}
@media only screen and (min-width: 992px) {
}
</style>

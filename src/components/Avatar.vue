<template>
  <div id='avatar'>
    <img src="https://res.cloudinary.com/dhc9nls3o/image/upload/v1531918174/dp.jpg" alt="Jethro Tanjay" />
  </div>
</template>

<script>

export default {
  name: 'avatar',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#avatar {
  background-color: #387d7a;
  overflow: hidden;
  padding: 10px;
  margin: auto;
  margin-top: 50px;
}
#avatar > img, #avatar {
  width: 250px;
  height: 250px;
  border-radius: 50%;
}
@media only screen and (max-width: 768px) {
  #avatar > img, #avatar {
    width: 100px;
    height: 100px;
  }
}
@media only screen and (min-width: 992px) {
}
</style>

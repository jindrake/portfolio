<template>
  <div id='content-container'>
    <div id='about-me' class='content'>
      <div id="content-heading">
        ABOUT ME
      </div>
      <p>
        A highly motivated software engineering student with experience on web projects involving different kinds of databases, front-end frameworks, and back-end technologies.
      </p>
      <div class="header">
        Education
      </div>
      <ul>
        <li>Central Philippine University - Bachelor of Science in Software Engineering (2014 - Present)</li>
        <li>Central Philippine University - Bachelor of Science in Information Technology (2014)</li>
      </ul>
      <div class="header">
        Awards and Certifications
      </div>
      <ul>
        <li>
          Achieved Proxor Level 2, a software development skills assessment rating recognized by IEEE.
        </li>
        <li>
          Ranked in the top 10 of Stack League, A coding competition that is powered by Proxor, and is supported by the following: IEEE, Worldbank, Startup IO.
        </li>
        <li>
          Completed the HTML5 training by Job & Esther.
        </li>
        <li>
          Completed the Mobile Game Development training by Job & Esther.
        </li>
      </ul>
      <div class="header">
        Projects
      </div>
      <div id="projects">
        Projects will be up soon
        <br>
        <img src="https://res.cloudinary.com/dhc9nls3o/image/upload/v1531918102/hourglass_loader.gif" >
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'content-container',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=PT+Sans');
.content {
  margin: auto;
  width: 80%;
  font-family: 'PT Sans';
}
#projects {
  text-align: center;
}
#projects > img {
  width: 300px;
}
#content-heading {
  width: 100%;
  text-align: center;
  font-weight: bold;
  font-size: 20px;
  margin-top: 20px;
}
.header {
  font-weight: bold;
  font-size: 20px;
  margin-top: 10px;
  margin-bottom: 10px;
  padding-bottom: 10px;
  border-bottom: 5px solid #18181833;
}
#content-container {
  height: 100%;
  position: absolute;
  left: 40%;
  top: 0px;
  width: 60%;
  font-size: 17px;
  text-align: left;
  overflow: auto;
}
li {
  margin: 10px;
  padding: 10px;
}
@media only screen and (max-width: 768px) {
  #content-container {
    width: 100%;
    top: 200px;
    height: 100%;
    left: 0px;
    font-size: 13px;
  }
  .header, #content-heading {
    text-align: center;
  }
  li {
    text-align: left;
    padding: 0px;
  }
  ul {
    text-align: left;
    padding: 0px;
    padding-left: 10px;
  }
  #projects > img {
    width: 200px;
  }
}
@media only screen and (min-width: 992px) {
}
</style>

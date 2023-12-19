<template>
<div id="navbar" class="container">
<div class="row">
  <div class="col" id="home"><a href="#home" class="links">Home</a></div>
  <div class="col"><a href="" class="links">About me</a></div>
  <div class="col"><a href="" class="links">Testimonials</a></div>
  <div class="col"><a href="" class="links">Projects</a></div>
  <div class="col"><a href="" class="links">Contact Me</a></div>
</div>
</div>
<div id="landing" class="container">
  <div class="row">
    <h2>Clayton</h2>
    <br>
    <h3>Adonis</h3>
  </div>
  <div class="row">
      <img id="img" src="./assets/1669108884251.jpg">
  </div>
</div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
}

#navbar {
  margin: 0;
  width: 30vw;
  background-color: aqua;
  text-align: center;
  border-bottom-right-radius: 10px;
  position: fixed;
}

a:link {
  text-decoration: none;
}

.links {
  color: brown;
  font-size: 1.5vh;
}

#img {
  width: 200px;
  height: 500px;
}
</style>
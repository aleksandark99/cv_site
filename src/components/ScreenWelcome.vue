<template>
  <div id="home" class="section welcome style">
    <div id="welcome_text">
      <h2>
        Hi, I am Aleksandar Kotur and this is my website. I am a software
        developer student from Serbia and in 2018 I enrolled The Faculty of
        Technical Sciences in Novi Sad, department of Software and information
        technology
      </h2>
    </div>
  </div>
</template>
<script>
export default {
  name: "ScreenWelcome",
};
</script>
<style >
#welcome_text {
  color: white(204, 0, 255);
  text-align: left;
  padding-right: 10%;
  padding-left: 10%;
  position: absolute;
  margin-top: 50px;
  top: 10%;


  font-family: "Comic Sans MS", cursive, sans-serif;
}
h1 {
  text-align: center;
}
.welcome {

  background-image: url("../assets/d2.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  image-rendering: optimizeSpeed;
  background-color: rgb(128, 128, 255);
}

@media screen and (max-width: 540px) {
  h2 {
    font-size: 30px !important;
  }
}
</style>
<template>
  <div class="section welcome style">
    <div id="welcome_text">
     
      <p>Hi, I am Aleksandar Kotur and this is my website, I am a student software developer from Serbia. In 2018 i enrolled
              The Faculty of Technical Sciences in Novi Sad, department of
              Software and information technology</p>

      <!-- <h1>HERE YOU CAN FIND MORE ABOUT ME </h1> -->
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
  /* color: rgb(255, 255, 255); */
  color: white(204, 0, 255)
;
  position: absolute;
  margin-top: 50px;
  top: 20%;
  left: 50%;
  transform: translate(-50%, -50%);
  opacity: 0.9;
    /* font-family: Impact, Charcoal, sans-serif	; */
  font-family: "Comic Sans MS", cursive, sans-serif;

}
h1 {
  text-align: center;
}
.welcome {
  /* background-image: url("../assets/welcome2.jpg"); */
  /* background-image: url("../assets/b3.svg"); */
  background-image: url("../assets/d2.png");
  /* opacity: 0.5; */
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  image-rendering: optimizeSpeed;
  background-color: rgb(128, 128, 255)
;
}
</style>
<template>
  <div class="section  welcome style">

    <div id="welcome_text">
            <h1>WELCOME</h1>

      <h1> I AM ALEKSANDAR KOTUR </h1>
            <h1>HERE YOU CAN FIND MORE ABOUT ME </h1>

      
      </div>
    
  </div>
</template>
<script>
export default {
  name: "ScreenWelcome",
};
</script>
<style >
#welcome_text{
  /* color: rgb(255, 255, 255); */
/* color: white; */
    position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
h1{
  text-align: center;
}
.welcome {
  
    background-image: url("../assets/welcome2.jpg");
    /* background-image: url("../assets/w.jpg"); */

    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    image-rendering: optimizeSpeed;
}
</style>
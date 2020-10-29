<template>
    <div class="main">
        <Navbar msg="AK"/>
        <ScreenWelcome/>
        <About/>
        <Skills/>
        <Contact/>
        
    </div>
</template>


<script>
import ScreenWelcome from "./ScreenWelcome.vue"
import About from "./About.vue"
import Navbar from "./NavBar.vue"
import Skills from "./Skills.vue"
import Contact from "./Contact.vue"

export default {
    name:"Main",
    components:{
        ScreenWelcome,
        About,
        Navbar,
        Skills,
        Contact
    }
}
</script>

<style >
.main{
  width:100%;
  min-height: 100vh;
      background: rgb(128, 128, 255);

    /* background: rgb(51, 153, 255); */

}
.section {
  height: 100vh;
}

.style{
   color: white; 

;
}
</style>
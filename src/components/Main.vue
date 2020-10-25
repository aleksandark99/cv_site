<template>
    <div class="main">
        <Navbar msg="AK"/>
        <ScreenWelcome/>
        <About/>

        
    </div>
</template>


<script>
import ScreenWelcome from "./ScreenWelcome.vue"
import About from "./About.vue"
import Navbar from "./NavBar.vue"

export default {
    name:"Main",
    components:{
        ScreenWelcome,
        About,
        Navbar
    }
}
</script>

<style >
.main{
  width:100%;
  min-height: 100vh;
}
.section {
  height: 100vh;
}

.style{
   color: white; 

;
}
</style>
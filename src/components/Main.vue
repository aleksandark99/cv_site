<template>
    <div class="main">
        <ScreenWelcome/>
        
    </div>
</template>


<script>
import ScreenWelcome from "./ScreenWelcome.vue"


export default {
    name:"Main",
    components:{
        ScreenWelcome
    }
}
</script>

<style >
.main{
  width: 100vw;
  
  min-height: 100vh;
}
.section {
  height: 100vh;
}
</style>
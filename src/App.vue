<template>
  <div id="app">
        <vue-headful title="Aleksandar Kotur"/>

   <Main/>


  
     <div>
     </div>

  </div>
</template>

<script>
import Main from './components/Main.vue'


export default {
  name: 'App',
  components: {
    Main

  }
}
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; 
   -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; 
  text-align: center;
   color: #2c3e50; */
    width: 100%;

}


</style>

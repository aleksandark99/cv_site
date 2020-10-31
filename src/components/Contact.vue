<template>
    <div id="contact">
<b-container class="contacts">
  <b-row id="red">
    <b-col cols="12" lg="3">  <b-img :src="require('../assets/gmail-512.png')"  v-bind="mainProps2" ></b-img><a href="mailto:aleksa.kotur@gmail.com">
 aleksa.kotur@gmail.com

    </a>
</b-col>
    <b-col cols="12" lg="3">  <b-img :src="require('../assets/p.png')"  v-bind="mainProps2" ></b-img>
    <a href="tel:+3810638512201">
    
     +381 0638512201
    </a>
     </b-col>
    <b-col cols="12" lg="3">  <b-img :src="require('../assets/g2.png')"  v-bind="mainProps2" ></b-img>
    <a href="https://github.com/aleksandark99" target="_blank">
      /aleksandark99
      </a> </b-col>
    <b-col cols="12" lg="3">  <b-img :src="require('../assets/linkedin.png')"  v-bind="mainProps2" ></b-img><a href="www.linkedin.com/in/aleksandar-kotur
" target="_blank">
      /aleksandar-kotur
      </a></b-col>


  </b-row>
</b-container>
    </div>
</template>

<script>
    export default {
        name:"Contact",
          data() {
    return {
      mainProps2: { width: 50, height: 50, class: "m3" },
    };
  },
    }
</script>

<style  scoped>
a{
  font-size: 16px;
  color: white;
}
#contact{
    background: #343a40;
padding: 0px;    color: white;
border-top: 3px white solid;
}
#red{
  padding-top: 15px;
    padding-bottom: 15px;

}
</style>
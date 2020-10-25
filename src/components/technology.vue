<template>
  <div id="teh">
    <p>{{text}}
    <b-img class="ims"
     :src="require(`../assets/${filename}`)"
      v-bind="mainProps"
    ></b-img>
</p>
  
  </div>
</template>

<script >
export default {
  name: "technology",
  props: {
    text: String,
    filename: String,
  },
    data() {
        return{
mainProps: { width: 50, height: 50},

        };
    }
};
</script>

<style scoped>
p{
    width: 250px;
}
.ims{
    float: right;

}


</style>
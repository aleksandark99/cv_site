<template>
  <div id="abscroll" class="aboutMeBackground1 style">
    <b-container fluid>
      <b-row align-self="stretch" class="text-center">
        <b-col cols="12" lg="6" class="text_style">
          <div class="d1">
            <div>
              <b-img
                :src="require('../assets/me1.jpg')"
                thumbnail="true"
                v-bind="mainProps"
                rounded="circle"
              ></b-img>
            </div>
            <h4>Aleksandar Kotur</h4>
            <p>
              I am a student software developer from Serbia. In 2018 i enrolled
              The Faculty of Technical Sciences in Novi Sad, department of
              Software and information technology. I have been programming since
              highschool. It started out as writing simple problem solving
              programs and it slowly evolved into console aplications. At one
              point i tried out game making which was fun and great learning
              experience for me but i decided to continue as software developer
              making web and desktop applications .
            </p>
          </div>
        </b-col>
        <b-col cols="12" lg="6" class="text_style">
          <div class="d2">
            <div>
              <b-img
                :src="require('../assets/ftn.jpg')"
                thumbnail="true"
                v-bind="mainProps2"
              ></b-img>
            </div>
            <a class="link" href="http://www.ftn.uns.ac.rs/1089714234/softverske-i-informacione-tehnologije--novi-sad-"  target="_blank">
              Faculty Of Technical Sciences, Department of Software and
              information technology</a
            >

            <p>
              I am always looking to improve my current skills and learn new
              ones and that is a reason i am looking for internship. I think
              that many things can be learnt on your own especially in this
              field but i also think that by working with other people one can
              improve their skills much faster and bring them to another level.
              <a class="link" href="">Down bellow </a>you can find a list of
              technologies i am familliar with as well as some projects i have
              worked on so far.
            </p>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>
<script>
export default {
  name: "About",
  components: {},
  data() {
    return {
      mainProps: { width: 250, height: 250, class: "m1" },
      mainProps2: { width: 400, height: 400, class: "m3" },
    };
  },
};
</script>
<style >



.aboutMeBackground1 {
  width: 100%;
  padding-left: -15px;
  padding-right: -15px;
  padding-top: 100px;
}

.container {
  padding-left: -15px;
  padding-right: -15px;
  height: 100%;
}

.d1 {
  padding-right: 50px;
  padding-left: 50px;
  border-top: 0px;
  border-bottom: 0px;
  border-left: 0px;
  border-style: dotted;
}
.d2 {
  padding-right: 50px;
  padding-left: 50px;
}
p {
  text-align: justify;
  font-family: "Comic Sans MS", cursive, sans-serif;
  font-size: 25px;
  padding: 10px;
}

.link {
  color: white;
  justify-content: center;
  text-align: center;
  font-size: 28px;
}
.link:hover {
  text-decoration: underline;
  color: white;
}
@media screen and (max-width: 992px) {
.d1{
  border-style: none;
}
}
</style>
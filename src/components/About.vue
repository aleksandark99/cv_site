<template>
  <div id="about" class="aboutMeBackground1 style">
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
              I have been programming since highschool. It started out as
              writing simple problem solving programs in C++. Over time I gained
              more and more knowledge and it slowly turned into console
              aplications. In my final year of highschool I decided to make a
              game for my final project. It was fun and great learning
              experience for me, but after I started attending university I
              leaned towards software developing, making web and desktop
              applications. I think I made the right choise because ever since I
              have been learning new things and it gives me a chance to meet new
              and interesting people with whom I can exchange experience, learn
              from and even work with!
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
            <a
              id="linkuni"
              class="link"
              href="http://www.ftn.uns.ac.rs/1089714234/softverske-i-informacione-tehnologije--novi-sad-"
              target="_blank"
            >
              <h4>
                Faculty Of Technical Sciences, Department of Software and
                information technology
              </h4>
            </a>

            <p>
              I am always looking to improve my current skills, learn new ones
              and that is a reason I am looking for <span style="text-decoration: line-through">internship </span>a job. I think that
              many things can be learnt on your own especially in this field,
              but I also think that by working with other people one can improve
              their skills much faster and bring them to another level.
            </p>
            <p>
              <a class="link" href="#skills"> Down bellow </a>you can find a
              list of technologies I am familliar with as well as some projects
              i have worked on so far.
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
  font-size: 20px;
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
#linkuni {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
}
@media screen and (max-width: 992px) {
  .d1 {
    border-style: none;
  }
}

@media screen and (max-width: 540px) {
  p {
    font-size: 16px;
  }
  h4 {
    font-size: 16px !important;
  }

  .d1 {
  padding-right: 10px;
  padding-left: 10px;

}
.d2 {
  padding-right: 10px;
  padding-left: 10px;
}
}
</style>
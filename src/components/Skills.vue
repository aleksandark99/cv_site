<template>
  <div id="skills">
    <b-container fluid>
      <b-row align-self="stretch" class="divleft">
        <b-col cols="12" lg="6">
          <div class="skillclass">

          <h3>Skills</h3>
          <p>-English B2</p>
          <p>-Java (Spring boot)</p>
          <p>-Sql</p>

          <p>-JavaScript</p>
          <p>-HTLM/CSS</p>
          <p>-Vue.js</p>
          <p>-C#</p>
          <p>-Android Studio Code</p>

        </div>
        </b-col>
        <b-col cols="12" lg="6">
          <div>
            <h3>Some Projects</h3>

            <div class="project">
              <h4>
                      <a class="gitlinks"
                  href="https://github.com/aleksandark99/wd_vue" target="_blank"
                >
                  Web cinema
                </a>
                <div class="images">
                  <b-img
                    :src="require('../assets/vue.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/java2.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/eclipse.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/tomcat.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/sqlite.png')"
                    v-bind="mainProps2"
                  ></b-img>
                </div>
              </h4>
              <p>
                Goal of this project was to make web application for cinema
                where users could search and bu tickets for projections. Java
                servlets were used on backend where Apache Tomcat was
                responsible for processing HTTP requests. I decided to focus
                more on frontend where i used vue.js and bootstrap-vue. My goal
                was to make responsive app that looked nice and was usable on
                all screens. I really liked how it turned out and vue became my
                preffered choice for frontend since then.
              </p>
            </div>
            <div class="project">
              <h4>
                <a class="gitlinks"
                  href="https://github.com/aleksandark99/Email-Client---Spring-Boot" target="_blank"
                >
                  Email Client - Spring Boot
                </a>

                <div class="images">
                  <b-img
                    :src="require('../assets/spring.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/intelij.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/mysql.png')"
                    v-bind="mainProps2"
                  ></b-img>
                </div>
              </h4>
              <p>
                This project is relaying on Spring technology on backend and
                Android on frontend. Our application is utilizing Java Mail API
                (for sending/receiving emails and for communicating with email
                servers) which was integrated in Spring environment, also, we
                used Hibernate ORM to communicate and persist data to MySQL
                database
              </p>
            </div>
            <div class="project">
              <h4>
                      <a class="gitlinks"
                  href="https://github.com/aleksandark99/Email-Client---Android" target="_blank"
                >
                  Email Client - Android
                </a>

                <div class="images">
                  <b-img
                    :src="require('../assets/android.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/sts.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/java2.png')"
                    v-bind="mainProps2"
                  ></b-img>
                </div>
              </h4>
              <p>
                This project is frontend for our Email Client app. Connection
                between two projects was realized using Retrofit3 library.
                Purpose of this project was to give user acess to all his emails
                across all his accounts in one place (gmail, yahoo or any other)
                as well to enable him to send, sort or even group emails to
                custom folders.
              </p>
            </div>

            <div class="project">
              <h4>
                                <a class="gitlinks"
                  href="https://github.com/aleksandark99/cv_site" target="_blank"
                >
                       Personal website
                </a>

                <div class="images">
                  <b-img
                    :src="require('../assets/vue.png')"
                    v-bind="mainProps2"
                  ></b-img>
                  <b-img
                    :src="require('../assets/netlify.png')"
                    v-bind="mainProps2"
                  ></b-img>
                </div>
              </h4>
              <p>
                I decided to make this website as alteranative to classic cv. I
                could have made it as simple html/css page but i decided to make
                it using vue with bootstrap and a little css because i find it
                more efficeint and practical.
              </p>
            </div>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "Skills",
  data() {
    return {
      mainProps2: { width: 50, height: 50, class: "m3" },
    };
  },
};
</script>

<style  scoped>
.gitlinks{
  color: white;
  font-size: 1.5rem;
}
img {
  margin-right: 5px;
}
#skills {
  font-family: Impact, Charcoal, sans-serif;
  padding-right: 50px;
  padding-left: 50px;
  border-top: 3px solid white;
  padding-top: 100px;
  color: white;
}
h3 {
  padding-bottom: 5px;
  border-bottom: 1px solid white;
  color: white;
}
h4 {
  color: white;
}
.project p {
  font-size: 16px;

  padding-left: 15px;
}

.skillclass p {
  font-size: 25px;

}
.images {
  display: inline;
}

@media screen and (max-width: 540px	){
   .skillclass p{
    font-size: 20px;
  }
}
</style>
<template>
  <div id="skills">
    <b-container fluid>
      <b-row align-self="stretch" class="divleft">
        <b-col cols="12" lg="6">
          <div class="skillclass">
            <h3>Skills</h3>
            <p>-B2 First - Cambridge Assessment English (Score 179) </p>
            <p>-Java (Spring boot)</p>
            <p>-Sql</p>
            <p>-MongoDB</p>
            <p>-Express.js</p>
            <p>-HTLM/CSS</p>
            <p>-Vue.js</p>
            <p>-Angular</p>
            <p>-Scala(Play)</p>
          </div>
        </b-col>
        <b-col cols="12" lg="6">
          <div>
            <h3>Some Projects</h3>

            <div class="project">
              <h4>
                <a
                  class="gitlinks"
                  href="https://github.com/aleksandark99/wd_vue"
                  target="_blank"
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
                where users could search and buy tickets for projections. Java
                servlets were used on backend where Apache Tomcat was
                responsible for processing HTTP requests. I decided to focus
                more on frontend where I used vue.js and bootstrap-vue. My goal
                was to make a responsive app that looked nice and was usable and looked decent on
                all devices. I really liked how it turned out and vue became my
                preferred choice for frontend since then.
              </p>
            </div>
            <div class="project">
              <h4>
                <a
                  class="gitlinks"
                  href="https://github.com/aleksandark99/Email-Client---Spring-Boot"
                  target="_blank"
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
                database.
              </p>
            </div>
            <div class="project">
              <h4>
                <a
                  class="gitlinks"
                  href="https://github.com/aleksandark99/Email-Client---Android"
                  target="_blank"
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
                <a
                  class="gitlinks"
                  href="https://github.com/aleksandark99/cv_site"
                  target="_blank"
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
                I decided to make this website as alteranative to classic cv.
                Instead of making it as a simple html/css page I decided to
                make it using vue with bootstrap and a little css because i find
                it more efficeint and practical.
              </p>
            </div>
          </div>
        </b-col>
      </b-row>
      <b-row align-self="stretch" class="divleft">
        <b-col cols="12" lg="12">
          <h2>Quick May 2021 Update</h2>
          <p>In the past few months I had an opportunity to work on few different projects. I experimented with both frontend and backend frameworks. On one of the projects I worked on this year I decided to try Angular and I really liked it and I will continue to work on mastering it. </p>
          <p>Although I got a really good impression from Angular,a much bigger impact on me left 2 backend frameworks: Express.js and Play framework in combination with Scala</p>
          <p>I will try to make this as short as possible. I was surprised how easy and fast it was to work with Express and MongoDB. Even configuring things that would take hours in other frameworks took only a few minutes in Express. That simplicity is reason i will try and do some upcoming projects with it. I mentioned MongoDB too. I used it on the same project as Express and I must admit that I liked it more than SQL databases and will also try to use in future projects.</p>
          <p>But Play framework and Scala really changed the way i looked at programming. It was my first experience with functional programming and it helped me improve, but not only in the field of functional programming but as a programmer. It was all thanks to internship at NovaLite and wonderful people that work there.</p>

          <h4>Plans for the future</h4>
          <p>At the time of writing this I am 2 exams from graduating. It was a wonderful experience. I met many people full of knowledge and experience, I learnt a lot of things and  made a lot of friends. That being said I believe it is time for me to look for a job where I can grow even more and meet more amazing people. </p>
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
.gitlinks {
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

@media screen and (max-width: 540px) {
  .skillclass p {
    font-size: 20px;
  }
  #skills {
  padding-right: 10px;
  padding-left: 10px;
  }
}
</style>
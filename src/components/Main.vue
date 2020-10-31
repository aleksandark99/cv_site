<template>
  <div class="main">
    <Navbar />
    <ScreenWelcome />
    <About />
    <Skills />
    <Contact />
  </div>
</template>


<script>
import ScreenWelcome from "./ScreenWelcome.vue";
import About from "./About.vue";
import Navbar from "./NavBar.vue";
import Skills from "./Skills.vue";
import Contact from "./Contact.vue";

export default {
  name: "Main",
  components: {
    ScreenWelcome,
    About,
    Navbar,
    Skills,
    Contact,
  },
};
</script>

<style >
.main {
  width: 100%;
  min-height: 100vh;
  background: rgb(128, 128, 255);
}
.main p:hover,
h1:hover,
h2:hover,
h3:hover,
h4:hover,
a:hover {
  color: yellow !important;
}

.section {
  height: 100vh;
}

.style {
  color: white;
}
</style>
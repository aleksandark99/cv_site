<template>
  <div id="n">
    <b-navbar fixed="top" toggleable="lg" type="dark" variant="dark ">
      <b-navbar-brand href="#home"
        ><b-img
          id="hi"
          :src="require('../assets/aks.svg')"
          rounded="circle"
          v-bind="mainProps2"
        ></b-img
      ></b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#home">Home</b-nav-item>
          <b-nav-item href="#about">About me</b-nav-item>
          <b-nav-item href="#skills">Skills</b-nav-item>
          <b-nav-item href="#contact">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>


<script>
export default {
  name: "Navbar",

  components: {},
  data() {
    return {
      mainProps2: { width: 50, height: 50, class: "m1" },
    };
  },
};
</script>

<style scoped>
.navbar {
  padding-top: 0;
  padding-bottom: 0;
}

.navbar-brand {
  margin-left: 20%;
}
.navbar-nav {
  margin-right: 20%;
}
.nav-link {
  color: white;
}
.navbar-dark .navbar-nav .nav-link {
  color: white;
}
.collapse {
  margin-right: 20px;
}
</style>
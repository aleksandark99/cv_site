<template>
  <div >
    <b-navbar toggleable="lg" type="dark" variant="dark ">
      <b-navbar-brand href="#">{{ msg }}</b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item href="#">About me</b-nav-item>
          <b-nav-item href="#">Skills</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>


<script>

export default {
  name: "Navbar",
  props: {
    msg: String,
  },
  components:{
    
  }
};
</script>

<style scoped>
.navbar-brand {
  margin-left: 20%;
}
.navbar-nav {
  margin-right: 20%;
}
.nav-link {
  color: white;
  /* background-color: white; */
}
.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 1);
}


</style>
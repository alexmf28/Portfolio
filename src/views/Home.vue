<template>
  <v-container class="fondoInicio" fluid>
    <span id="hello"><Hello /></span>
    <span id="aboutMe"><AboutMe /></span>
    <span id="projects"><Projects /></span>
    <span id="contact"><Contact /></span>
    <v-footer dark class="d-flex justify-center align-center"
      ><h3>alexmf28</h3></v-footer
    >
  </v-container>
</template>

<script>
import Hello from "../components/Hello.vue";
import AboutMe from "../components/AboutMe.vue";
import Projects from "../components/Projects.vue";
import Contact from "../components/Contact.vue";

export default {
  name: "Home",

  components: {
    Hello,
    AboutMe,
    Projects,
    Contact,
  },
};
</script>
<style>
.fondoInicio {
  background: black;
}
html {
  scroll-behavior: smooth;
}
</style>

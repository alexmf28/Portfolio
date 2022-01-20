<template>
  <v-container class="fondoInicio" fluid>
    <Hello />
    <span id="aboutMe"><AboutMe /></span> 
    <Projects />
  </v-container>
</template>

<script>
import Hello from "../components/Hello.vue";
import AboutMe from "../components/AboutMe.vue";
import Projects from "../components/Projects.vue";

export default {
  name: "Home",

  components: {
    Hello,
    AboutMe,
    Projects,
  },
};
</script>
<style>
.fondoInicio {
  background: black;
}
html{
  scroll-behavior: smooth;
}
</style>

<template>
  <v-row class="text-center fondoHome">
    <v-col
      class="white--text d-flex flex-column align-center justify-center inicio"
      md="4"
    >
      <h1 class="display-1 font-weight-bold mb-3">HELLO MY NAME IS ALEXIS</h1>

      <p class="subtitle-1 font-weight-regular">I'M A FRONT-END DEVELOPER</p>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "Hello",

  data: () => ({}),
};
</script>
<style>
.fondoHome {
  background-image: url(../assets/homeGif.gif);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  height: 100vh;
}

.fondoHome a {
  text-decoration: none;
  color: white;
}
.inicio {
  margin-left: 5%;
  margin-right: 5%;
  margin-top: 10%;
}
</style>
